# Medio sumador HA

$A$ y $B$ son lo sumandos
$S$  es la salida
$C$ es el carreo de la salida

$m = 2^n$
$n=2$ variables $A$ y $B$
$m = 2^2 =$ 4 combinaciones

|  -  | $A$ | $B$ | $C$ |   $\to$    | $S$ |         $\to$         |
|:---:|:---:|:---:|:---:|:----------:|:---:|:---------------------:|
|  0  |  0  |  0  |  0  |            |  0  |                       |
|  1  |  0  |  1  |  0  |            |  1  | $m_1 = \overline{A}B$ |
|  2  |  1  |  0  |  0  |            |  1  | $m_2 = A\overline{B}$ |
|  3  |  1  |  1  |  1  | $m_3 = AB$ |  1  |                      |

---
Resolver con mintérminos

**Acarreo de salida**

$$\displaylines{
c= m_3\\
c = AB\\
}$$

**Suma**

$$\begin{array}{l}
s = m_1 + m_2 = \sum m (1,2) \\
s = \overline{A}B + A\overline{B} = A\oplus B
\end{array}$$

> or exclusiva (xor) 7486 uno impar

|  A  |  B  | A $\oplus$ B |      $\to$      |
|:---:|:---:|:------------:|:---------------:|
|  0  |  0  |      0       |                 |
|  0  |  1  |      1       | $\overline{A}B$ |
|  1  |  0  |      1       | $A\overline{B}$ |
|  1  |  1  |      0       |                 |

> $A\oplus B = \overline{A}B + A\overline{B}$

---
![](attachments/medio-sumador-1.jpeg)

Figura 1. Medio sumador - Swich B encendido, `xor` activado

![](attachments/medio-sumador-2.jpeg)

Figura 2. Medio sumador - Switches A y B encendidos, `and` activado

---
### Conclusión

Para concluir, es importante conocer todas las "propiedades" que sen encuentran en el Álgebra booleana. En este ejercicio podemos observar que se utilizó el xor (o exclusivo) el cual solo deja pasar corriente solo cuando tiene una entrada de energía, pero no cuando se tienen ambas o ninguna. 

---
### Referencias

- Notas del curso