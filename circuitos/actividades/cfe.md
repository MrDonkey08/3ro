# Actividad CFE

## Datos

| Electrodométicos    | Cantidad | Horas por día | Consumo en Watts |
| ------------------- |:--------:|:-------------:|:----------------:|
| Lavadora            |    2     |      1/2      |       600        |
| Refrigerador        |    1     |      24       |       350        |
| Horno de microondas |    1     |      1/5      |       700        |
| Secadora            |    1     |      1/2      |       3000       |
| Parrilla eléctrica  |    1     |       3       |       1700       |
| Televisores         |    3     |       4       |        80        |
| Luminarias          |    7     |       4       |        12        |
| Computadoras        |    1     |       5       |       130        |
| Consola             |    1     |       3       |        80        |

## Procedimiento


> [!INFO] Notación
> 
> - Energía Bimestral = $E_{B}$
> - Potencia = $P$
> - Voltaje = $V$
> - Watts = $W$
> - Amper = $A$
> - Resitencia = $R$
> - Tiempo total bimestral = $T_{B}$
> - Día = $d$
> - Cuota Bimestral = $C_{B}$

### Lavadoras

**Consumo energético:**


$$\displaylines{
P = 2 ⋅ 600\ W = 1.2\ kW \\
T_{B} = \frac{1}{2} ⋅ \frac{h}{d} ⋅ 60\ d = 35 \ h\\ 
E_{B} = 1.2\ kW ⋅ 15\ h = 36\ kWh
}$$

**Resistencia equivalente:**

$$R = \frac{V^{2}}{P} = \frac{(127\ V)^{2}}{{1.2\ kW}} = \frac{16.129\ kV^{2}}{1.2\ kW} \approx 13.44\ Ω$$

**Corriente:**

$$I = \frac{P}{V} = \frac{1.2\ kW}{127\ V} \approx 9.45\ A$$

### Refrigerador

$$\displaylines{
P = 350\ W \\
T_{B} = 24  \frac{h}{d} ⋅ 60\ d = 144\ h\\ 
E_{B} = 350\ W ⋅ 144\ h = 50.4\ kWh
}$$

**Resistencia equivalente:**

$$R = \frac{16.129\ kV^{2}}{350\ W} \approx 46.8\ Ω$$

**Corriente:**

$$I = \frac{350\ W}{127\ V} \approx 2.75\ A$$

### Horno de microondas

$$\displaylines{
P = 700\ W \\
T_{B} = \frac{1}{5} ⋅ \frac{h}{d} ⋅ 60\ d = 12\ h\\ 
E_{B} = 700\ W ⋅ 12\ h = 84\ kWh
}$$

**Resistencia equivalente:**

$$R = \frac{16.129\ kV^{2}}{700\ W} \approx 23.04\ Ω$$

**Corriente:**

$$I = \frac{700\ W}{127\ V} \approx 5.51\ A$$


### Secadora

$$\displaylines{
P = 3\ kW \\
T_{B} = \frac{1}{2} ⋅ \frac{h}{d} ⋅ 60\ d = 30\ h\\ 
E_{B} = 3\ kW ⋅ 12\ h = 36\ kWh
}$$

**Resistencia equivalente:**

$$R = \frac{16.129\ kV^{2}}{3\ kW} \approx 53.76\ mΩ$$

**Corriente:**

$$I = \frac{3\ kW}{127\ V} \approx 23.62\ A$$

### Parrilla eléctrica

$$\displaylines{
P = 1.7\ kW \\
T_{B} = 3\ \frac{h}{d} ⋅ 60\ d = 180\ h\\ 
E_{B} = 1700\ W ⋅ 180\ h = 306\ kWh
}$$

**Resistencia equivalente:**

$$R = \frac{16.129\ kV^{2}}{1.7\ kW} \approx 9.49\ Ω$$

**Corriente:**

$$I = \frac{1.7\ kW}{127\ V} \approx 13.39\ A$$



### Televisores

$$\displaylines{
P = 3 ⋅ 80\ W = 240\ W\\
T_{B} = 4\ \frac{h}{d} ⋅ 60\ d = 240\ h\\ 
E_{B} = 240\ W ⋅ 240\ h = 57.6\ kWh
}$$

**Resistencia equivalente:**

$$R = \frac{16.129\ kV^{2}}{240\ W} \approx 67.20\ Ω$$

**Corriente:**

$$I = \frac{240\ W}{127\ V} \approx 1.89\ A$$

### Luminarias

$$\displaylines{
P = 7 ⋅ 12\ W = 84\ W\\
T_{B} = 4\ \frac{h}{d} ⋅ 60\ d = 240\ h\\ 
E_{B} = 84\ W ⋅ 240\ h = 20.16\ kWh
}$$

**Resistencia equivalente:**

$$R = \frac{16.129\ kV^{2}}{84\ W} \approx 192.01\  Ω$$

**Corriente:**

$$I = \frac{84\ W}{127\ V} \approx 6.61\ A$$

### Computadora

$$\displaylines{
P = 130\ W\\
T_{B} = 5\ \frac{h}{d} ⋅ 60\ d = 300\ h\\ 
E_{B} = 130\ W ⋅ 300\ h = 39\ kWh
}$$
**Resistencia equivalente:**

$$R = \frac{16.129\ kV^{2}}{130\ W} \approx 124.07\ Ω$$

**Corriente:**

$$I = \frac{130\ W}{127\ V} = 1.02 \ A$$

### Consola

$$\displaylines{
P = 80\ W\\
T_{B} = 3\ \frac{h}{d} ⋅ 60\ d = 180\ h\\ 
E_{B} = 80\ W ⋅ 180\ h = 14.4\ kWh
}$$

**Resistencia equivalente:**

$$\displaylines{
R = \frac{16.129\ kV^{2}}{80\ W} \approx 201.61\  Ω
}$$

**Corriente:**

$$I = \frac{80\ W}{127\ V} \approx 0.62\ A$$


### Total

**Consumo:**

$$E_{B_{T}} = \sum E_{B} = (36 + 50.4 + 84 + 36 + 306 + 57.6 + 20.16 + 39 + 14.4)\ kWh = 643.56\ kWh$$
**Resistencia equivalente:**

$$R_{T} = \sum R = (13.44  + 46.8 + 23.04 + 53.76 + 9.49 + 67.8 + 192.01 + 124.07 + 201.61)\  Ω = 723.02 \ Ω$$

**Corriente:**

$$I_{T} = \sum I = (9.45 + 2.75 + 5.51 + 23.62 + 13.39 + 1.89 + 6.61 + 1.02 + 0.62)\ A = 64.82\ A$$

### Cuota bimestral

> [!INFO] Tarifas
> 
> - Básico:  $0.865 --------150kw
> - Intermedio: $1.04------130kw
> - Excedente: $3.066

$$C_{B} = \$0.865 \cdot 150\ kW + \$1.04 \cdot 130\ kW + \$3.066 \cdot(643.56 - 280\ kW) \approx \$(129 + 135.2 + 1,112.95) = \$1377.15 $$

## Resultados

**Consumo bimestral total:** 643.56 kWh
**Resitencia equivalente total:** 723.02 Ω
**Corriente total:** 64.82 A
**Cuota bimestral:** \$1377.15