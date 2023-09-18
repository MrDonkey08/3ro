# Decodificador de BCD a 7 segmentos

## Archivo pld

```pld
Name     bcd7s ;
PartNo   00 ;
Date     27/04/2023 ;
Revision 01 ;
Designer JRAY ;
Company  CUCEI ;
Assembly None ;
Location  ;
Device   g22v10 ;

/* *************** INPUT PINS *********************/
PIN 1 = A                        ; /*                                 */ 
PIN 2 = B                        ; /*                                 */ 
PIN 3 = C                        ; /*                                 */ 
PIN 4 = D                        ; /*                                 */ 

/* *************** OUTPUT PINS *********************/
PIN 14 = SEGA                    ; /*                                 */ 
PIN 15 = SEGB                    ; /*                                 */ 
PIN 16 = SEGC                    ; /*                                 */ 
PIN 17 = SEGD                    ; /*                                 */ 
PIN 18 = SEGE                    ; /*                                 */ 
PIN 19 = SEGF                    ; /*                                 */ 
PIN 20 = SEGG                    ; /*                                 */ 

SEGA = ((!A) & (!B) & (!C) & (D)) # ((B) & (!C) & (!D));
SEGB = ((B) & (!C) & (D)) # ((B) & (C) & (!D));
SEGC = (!B) & (C) & (!D);
SEGD = ((!A) & (!B) & (!C) & (D)) # ((B) & (!C) & (!D)) # ((B) & (C) & (D));
SEGE = ((B) & (!C)) # D;
SEGF = ((!A) &(!B) & (D)) # ((!B) & (C))# ((C) & (D));
SEGG = ((!A) & (!B) & (!C)) # ((B) & (C) & (D));
```

## Archivo jed

```jed

CUPL(WM)        5.0a  Serial# 60008009
Device          g22v10  Library DLIB-h-40-1
Created         Fri Apr 28 09:35:54 2023
Name            bcd7s 
Partno          00 
Revision        01 
Date            27/04/2023 
Designer        JRAY 
Company         CUCEI 
Assembly        None 
Location        
*QP24 
*QF5892 
*G0 
*F0 
*L01472 00000000000000000000000011111111
*L01504 11111111111111111111111111111111
*L01536 11111011101110111111111111111111
*L01568 11111111111111111111011101110111
*L01600 11111111111111111111111111110000
*L02144 00000000000011111111111111111111
*L02176 11111111111111111111111110111011
*L02208 11110111111111111111111111111111
*L02240 11111111101101111111111111111111
*L02272 11111111111111111111111101110111
*L02304 11111111111111111111111111110000
*L02880 00000000000000000000000011111111
*L02912 11111111111111111111111111111111
*L02944 11111111011110111111111111111111
*L02976 11111111111111111111111111110111
*L03008 11111111111111111111111111110000
*L03648 00001111111111111111111111111111
*L03680 11111111111111111011101110110111
*L03712 11111111111111111111111111111111
*L03744 01111011101111111111111111111111
*L03776 11111111111101110111011111111111
*L03808 11111111111111111111000000000000
*L04288 00000000000000000000000011111111
*L04320 11111111111111111111111111111111
*L04352 11111111101101111011111111111111
*L04384 11111111111111110000000000000000
*L04864 00000000000000000000111111111111
*L04896 11111111111111111111111111111111
*L04928 11110111101101111111111111111111
*L04960 11111111111111110111011110111111
*L04992 11111111111111111111111100000000
*L05344 00000000000000000000000011111111
*L05376 11111111111111111111111111111111
*L05408 11111011101110110111111111111111
*L05440 11111111111111111111011110111011
*L05472 11111111111111111111111111110000
*L05792 00000000000000000000001111111111
*L05824 11110011000000110000001000000000
*C7915
*7451
```

<div style="page-break-after: always;"></div>

## Simulación en Proteus

![ | center](attachments/bcd-2-7seg-1.png)

<center>Fig. 1 Circuito BCD  a 7 segmentos - 5</center>

![ | center](attachments/bcd-2-7seg-2.png)

<center>Fig. 2 Circuito BCD  a 7 segmentos - 8</center>

<div style="page-break-after: always;"></div>

## Circuito

![center | 400](attachments/c_bcd-2-7seg-1.png)

<center>Fig. 3 - Circuito BCD  a 7 segmentos - 0</center>

![ center | 400](attachments/c_bcd-2-7seg_2.png)

<center>Fig. 4 - Circuito BCD  a 7 segmentos - 0</center>

![ center | 400](attachments/c_bcd-2-7seg_3.png)

<center>Fig. 5 - Circuito BCD  a 7 segmentos - 9</center>

<div style="page-break-after: always;"></div>

## Conclusión

Para concluir es importante aprender el funcionamiento de display de 7 segmentos para poder trabajar correctamente con él, es decir, saber cómo programarlo y cómo trabajarlo al momento de hacer el sistema.

<div style="page-break-after: always;"></div>

# Referencias

- Notas del curso