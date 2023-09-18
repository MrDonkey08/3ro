---
title: Lógica de Función Fija
author: Alan Yahir Juárez Rubio

aliases: compuerta, logica, cmos, ttl
tags: sistemas-digitales

creation date: 14-02-2023
last modification date: 14-02-2023

type: Nota de clase
---

---
### Lógica de Función Fija

Existen dos tecnología de circuitos integrados digitales que se usan para implementar las puertas lógicas básicas: CMOS y TTL

Las operaciones lógicas NOT, AND, OR, NAND, NOR, OR-exclusiva son las mismas, independientement la teecnología...

---
### Compuertas Lógicas

El término CMOS corresponde a Complementary Meta-Oxide Semiconductor (semiconductor metal-óxido complementario) y se implementa con un tipo de transistor en efecto campo.

TTL (TransistorTransisistor Logic, lógica, transistor.transistor) y se implementa mediante transistorse bipolares.

> [!NOTE]
> 
> La diferenccia entre CMOS y TTL se encuentra en las caracteristecas de funcionamiento, al como la velocidad de conmutación (retardo de propagación), la disipación de potencia, la inmunidad al ruido y otros parámetros

---
> [!EXAMPLE]+ Ejercicio en clase
> 
> $R=\frac{V}{I} = \frac{5\ V}{(15\ mah) \cdot 10^{-3} } = 333\ \ohm$

> [!INFO]
> 
>Cantidad de corriente para encender un led: 5 o 12 mah

---

TTL tiene altas velocidades de conmutación y una enorme variedad de dispositivos.

La tecnologóa CMOS ofrece mucho menor disipación  de potencia sobre TTL

CMOS tiene la desventaja de que puede descomponerse por la estática.

---
### Series CMOS 

Las categorias de CMOS en términos de **tensión de alimentación** continua son 
- la serie CMOS de:
	- 5 V
	- 3.3 V
	- 2.5 V
	- 1.8 V

Las series CMOS de más baja tensión son el resultado de un desarrollo más reciente de un eswuerzo por deducir la disipación de potencia. Puesto que la disipación de potencia es proporcional al cuadrado de la tención una reducción de 5 V a 3.3 V, disminuye en un 34 %

---
La familia CMOS difieren en sus caracteristicas de funcionamient y se designan mediante los prefijos 74 o 54, seguidos de una letra o letsras que indican la serise y, a continuación, un número que indica el tipo de dispositivo lógico.

El prefijo 74 indica que se trata de un dispositivo comercial de propórit geneal, y el prefijo 54 indica que es un dispositivo militar para aplicacione en entorno más exigentes.

<!-- Domótica: -->
<div style="page-break-after: always;"></div>

---
La serie básica de 5V y sus denominacionses son las siguientes:
- 74 HC...

---
Existen series que combinan la tecnología CMOS y TTL y se denominan BICMOS. La series básica BiCMOS y sus denominaciones son las siguientes

74BCT.BICMOS
74ABT.BICMOS avanzada
74LVT. BiCMOS de baja tensión
74ALB. BiCMOS de baja tensión

---
### La tecnología TTL

47: TTL...

---
> [!INFO]
> 
> La impedencia tiene una componente capasitiva y una inductiva.

---
### Referencias

- Notas de clase.