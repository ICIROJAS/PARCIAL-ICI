# FUNDAMENTOS DE PROGRAMACION
## PROBLEMAS RESUELTOS EN CLASE
#### DIAGRAMA 1
![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/PROGRAMA1.png)

**PRUEBA DE ESCRITORIO**
| msg | salida |
| ----------- | ----------- |
| "28 DE AGOSTO DE 2022" |28 DE AGOSTO DE 2022 |
#### DIAGRAMA 2
![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%202.png)

**PRUEBA DE ESCRITORIO**
| msg | salida |
| ----------- | ----------- |
| "ISAAC" |ISAAC |
#### DIAGRAMA 3
![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%203.png)

**PRUEBA DE ESCRITORIO**
| proceso | msg |salida|
| ----------- | ----------- |----------- |
 | num="isaac" |num | isaac |
 #### DIAGRAMA 4
 ![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%204.png)
 
 **PRUEBA DE ESCRITORIO**
| msg | a,b | n=a+b | n x n | salida |
| ----------- | ----------- |----------- |----------- |----------- |
|"dame 2 nnumeros enteros"| 4,2 | n=4+2 | 6 x 6| 36 |
#### DIAGRAMA 5
 ![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%205.png)
  
  **PRUEBA DE ESCRITORIO**
  | proceso | msg |salida|
| ----------- | ----------- |----------- |
 | num="alex" |"hola",num | isaac |
 #### DIAGRAMA 6
 ![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%206.png)
 
 **PRUEBA DE ESCRITORIO**
 | msg | nom |msg|salida |
| ----------- | ----------- |----------- |----------- |
 | "como te llamas" |isaac | "Buen dia",nom |buen dia isaac  |
 #### DIAGRAMA 7
 ![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%207.png)
 
  **PRUEBA DE ESCRITORIO**
  | 2*2 | salida |
| ----------- | ----------- |
| 4 | 4 |
 #### DIAGRAMA 8
 ![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%208.png)
 
 **PRUEBA DE ESCRITORIO**
 | proceso | n*n |salida |
| ----------- | ----------- |----------- |
 | n=5 | 5*5 | 25 |
 #### DIAGRAMA 9
 ![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%209.png)
 
 **PRUEBA DE ESCRITORIO**
 | msg | n= |n*n|salida |
| ----------- | ----------- |----------- |----------- |
 | "cual es el valor de n" |5 | 5*5 |25  |
#### DIAGRAMA 10
![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%2010.png)

 **PRUEBA DE ESCRITORIO**
| msg | a_nac | msg |a_act |a_act-a_nac |salida|
| ----------- | ----------- |----------- |----------- |----------- |----------- |
|"dame tu año de nacimeinto"| 2004 |"dame el año actual" | 2022|2022-2004 |18|
#### DIAGRAMA 11
![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%2011.png)

**PRUEBA DE ESCRITORIO**
|corridas| msg | a_nac | a_nac=>0 | msg |a_act |a_act=>0 |a_act-a_nac |salida|
| ----------- | ----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |
|1|"dame tu año de nacimeinto"| 2004 |No|"dame el año actual" | 2022|No|2022-2004 |18|
|   | msg | a_nac | a_nac=>0 | msg |salida|
|2|"dame tu año de nacimeinto"| 2004 |si|"No puede ser 0"|No puede ser 0|
#### DIAGRAMA 12
![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%2012.png)

**PRUEBA DE ESCRITORIO**
| s=s+c | cont<=10 |c=c+2|s=s+c|cont<=10| c=c+2|s=s+c| cont<=10  | msg |salida|
| ----------- | ----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |
 | 0+1  |no| 1+2 |1+3  | no   | 4+2| 6+4   | si   |   s  | 10   |  
#### DIAGRAMA 13
![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%2013.png)

**PRUEBA DE ESCRITORIO**
|cont=1|cont|cont<=10|cont=cont+1|cont|cont<=10|cont=cont+1|cont|cont<=10|cont=cont+1|cont|cont<=10|cont=cont+1|cont|cont<=10|cont=cont+1|cont|cont<=10|cont=cont+1|cont|cont<=10|cont=cont+1|cont|cont<=10|cont=cont+1|cont|cont<=10|cont=cont+1|cont |cont<=10 | 
| ----------- | ----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |
 | 1 | 1 | No |1+1  | 2 | No | 2+1| 3  | No | 3+1  |  4  |  No | 4+1 | 5 |No | 5+1 | 6 |No | 6+1 | 7 |No | 7+1 | 8|No | 8+1 | 9|No | 9+1 | 10| Si|
#### DIAGRAMA 14
![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%2014.png)

**PRUEBA DE ESCRITORIO**
|corridas| msg | a_nac | msg |a_act |a_act=>0 |a_act-a_nac |salida|
| ----------- | ----------- |----------- |----------- |----------- |----------- |----------- |----------- |
|1|"dame tu año de nacimeinto"| 2004 |"dame el año actual" | 2022|No|2022-2004 |18|
|   | msg | a_nac | msg| a_act |a_act=>0 |msg |
|2|"dame tu año de nacimeinto"| 2004 |"dame el año actual"| 2002 |  si| "el año actual no puede ser menor al año de nacimiento" |
#### DIAGRAMA 15
![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%2015.png)

**PRUEBA DE ESCRITORIO**
| s=s+c | cont<=10 |c=c+2|s=s+c|cont<=10| c=c+2|s=s+c| cont<=10  | msg |salida|
| ----------- | ----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |
 | 0+2  |no| 2+2 |2+4  | no   | 4+2| 6+6   | si   |   s  | 12   |
#### DIAGRAMA 16
![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%2016.png)

**PRUEBA DE ESCRITORIO**
| c*2 | cont<=5|c++|salida |
| ----------- | ----------- |----------- |----------- |
 |c*2 |c<=5|c++ |Numeros pares  |
 #### DIAGRAMA 17
![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%2017.png)
**PRUEBA DE ESCRITORIO**

