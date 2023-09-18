# Sumador completo FA

$A$, $B$ y $C$ son lo sumandos
$S$  es la salida
$K$ es el carreo de la salida

$m = 2^n$
$n = 3$ variables $A$, $B$ y $C$
$m = 2^3 =$ 8 combinaciones

|  -  | $A$ | $B$ | $C$ | $K$ |      $\to$       | $S$ |             $\to$             |
|:---:|:---:|:---:|:---:|:---:|:----------------:|:---:|:-----------------------------:|
|  0  |  0  |  0  |  0  |  0  |                  |  0  |                               |
|  1  |  0  |  0  |  1  |  0  |                  |  1  | $\overline{A}\ \overline{B}C$ |
|  2  |  0  |  1  |  0  |  0  |                  |  1  |  $\overline{A}B\overline{C}$  |
|  3  |  0  |  1  |  1  |  1  | $\overline{A}BC$ |  0  |                               |
|  4  |  1  |  0  |  0  |  0  |                  |  1  | $A\overline{B}\ \overline{C}$ |
|  5  |  1  |  0  |  1  |  1  | $A\overline{B}C$ |  0  |                               |
|  6  |  1  |  1  |  0  |  1  | $AB\overline{C}$ |  0  |                               |
|  7  |  1  |  1  |  1  |  1  |      $ABC$       |  1  |             $ABC$             |


---
Resolver con mintérminos


$$\begin{array}{l|l} \tag {Acarreo | Suma}
K = \sum m(3, 5, 6, 7)  & S = \sum m(1, 2, 4, 7) \\
K = \overline{A}BC + A\overline{B}C + AB\overline{C} + ABC & S = \overline{A}\ \overline{B}C + \overline{A}B\overline{C} + ABC \\
K = C(\overline{A}B + A\overline{B}) + AB(\overline{C} + C) & S = \overline{A}(\overline{B}C + B\overline {C}) + A(\overline{B}\ \overline{C}+BC) \\
K = C(A\oplus B) + AB & S = \overline{A} (B\oplus C) + A(\overline{B\oplus C}) \\
& S = A\oplus (B\oplus C) \\
& S = A\oplus B\oplus C
\end{array}$$

---
![](attachments/sumador-completo.jpeg)

Figura 1. Sumador completo HA

---
### Conclusión

Si bien esta actividad fue un tanto compleja, fue interesante el desarrollarla ya que nos indujo a conseguir un sistema que funciona de una manera un tanto curiosa. A mi parecer, ejercicios de este estilo son importantes para inducirnos a sistemas más complejos y con mayor relevancia.
<div style="page-break-after: always;"></div>

---
### Referencias

- Notas del curso