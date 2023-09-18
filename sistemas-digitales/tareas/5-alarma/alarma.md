
# Alarma

Diseñar una alarma de 3 variables de entrada (A, B, C) y una salida (S)

$$\begin{array}{l}
m = 2^n\\
n = \text{variables}\\
m = \text{combinaciones}\\
m = 2^3 = 8
\end{array}$$
|  m  |  A  |  B  |  C  |  S  |                        |
|:---:|:---:|:---:|:---:|:---:|:----------------------:|
|  0  |  0  |  0  |  0  |  0  |                        |
|  1  |  0  |  0  |  1  |  0  |                        |
|  2  |  0  |  1  |  0  |  0  |                        |
|  3  |  0  |  1  |  1  |  1  | $m_3 = \overline{A}BC$ |
|  4  |  1  |  0  |  0  |  0  |                        |
|  5  |  1  |  0  |  1  |  1  | $m_5 = A\overline{B}C$ |
|  6  |  1  |  1  |  0  |  0  |                        |
|  7  |  1  |  1  |  1  |  1  | $m_7 = ABC$                       |

$$\begin{array}{ll}
S(A, B, C) & = \sum m (3,5,7)\\
& = \overline{A} BC + A\overline{B}C + ABC\\
& = BC(\overline{A}+A) + A\overline{B}C\\
& = BC(1) + A\overline{B}C & = BC + A\overline{B}C\\
&& = C(B + A\overline{B})\\
&& = C(B + \overline{B}A)\\
&& = C(B+A)\\
&& = CB+CA
\end{array}$$

![](attachments/alarma-1.jpeg)

![](attachments/alarma-2.jpeg)

![](attachments/alarma-3.jpeg)

![](attachments/alarma-4.jpeg)

---
Convertir a solo compuertas NAND

(no and, 7400), la alarma de 3 variables ya encontrada

$S = CB + CA$
$S= \overline{\overline{CB + CA}}$, $\overline{\overline{a}} = a$ Involución
$S = \overline{\overline{CB}\cdot \overline{CA}}$, $\overline{a + b} = \overline{a}\cdot \overline{b}$ Teorema de DeMorgan

![](attachments/alarma-1-nand.jpeg)

![](attachments/alarma-2-nand.jpeg)

![](attachments/alarma-3-nand.jpeg)

---
## Conclusion

Para finalizar, es importante el uso de la lógica matemática para la implementación de circuitos electrónicos y su debida optimización para la reducción de costes, de uso de recursos.

---
## Referencias

- Notas del curso.