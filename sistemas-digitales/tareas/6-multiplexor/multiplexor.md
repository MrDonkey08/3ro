# Multiplexor

Diseñar un multiplexor (selector de datos, MUX) de:
- Dos variables de entrada $I_0$,  $I_1$
- Un selector de entrada ($S$)
- Una salida $Y$

Si $S=0 \to Y=I_0$
Si $S=1 \to Y= I_1$

---
Tabla del MUX $2\times 1$

$$\begin{array}{l}
m = 2^n\\
n = 3\\
m = 2^3 = 8\text{ combinaciones}
\end{array}$$

| $m$ | $S$ | $I_1$ | $I_0$ | $Y$ | $\to$                                   |
| --- | --- | ----- | ----- | --- | --------------------------------------- |
| 0   | 0   | 0     | 0     | 0   |                                         |
| 1   | 0   | 0     | 1     | 1   | $m_1 = \overline{S}\ \overline{I_1}I_0$ |
| 2   | 0   | 1     | 0     | 0   |                                         |
| 3   | 0   | 1     | 1     | 1   | $m_3 = \overline{S}I_1 I_0$             |
| 4   | 1   | 0     | 0     | 0   |                                         |
| 5   | 1   | 0     | 1     | 0   |                                         |
| 6   | 1   | 1     | 0     | 1   | $m_6 = S \overline{I_1}I_0$             |
| 7   | 1   | 1     | 1     | 1   | $m_7 = S I_1 I_0$                       |

---
Resolver con Álgebra de Boole

$$\begin{array}{l}
\overline{S}\ \overline{I_1}I_0 
+ \overline{S}I_1I_0
+ SI_1\overline{I_0}
+ SI_1I_0
\\
\overline{S}I_0 (\overline{I_1}+I_1) 
+ SI_1(\overline{I_0}+I_0)
\\
\overline{S}I_0 (1) + SI_1(1)
\\
\overline{S}I_0+ SI_1
\end{array}$$
---

![600](attachments/multiplexor-1.jpeg)

Figura 1. Multiplexor - switches apagados

![600](attachments/multiplexor-2.jpeg)

Figura 2. Multiplexor - Switch $S$ e $I_0$  encendidos

![600](attachments/multiplexor-3.jpeg)

Figura 3. Multiplexor - Switch $I_1$ encendido

![600](attachments/multiplexor-4.jpeg)

Figura 4. Multiplexor - Switch $S$ e $I_1$  encendidos

---
### Conclusion

Para finalizar, es de vital importancia aprender a convertir una expresión booleana a forma de circuito. En esta actividad aprendí el símbolo del `not` y el cómo funciona en un circuito.
<div style="page-break-after: always;"></div>

---
### Referencias

- Notas del curso.