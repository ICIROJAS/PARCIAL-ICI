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
|"dame tu a??o de nacimeinto"| 2004 |"dame el a??o actual" | 2022|2022-2004 |18|
#### DIAGRAMA 11
![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%2011.png)

**PRUEBA DE ESCRITORIO**
|corridas| msg | a_nac | a_nac=>0 | msg |a_act |a_act=>0 |a_act-a_nac |salida|
| ----------- | ----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |
|1|"dame tu a??o de nacimeinto"| 2004 |No|"dame el a??o actual" | 2022|No|2022-2004 |18|
|   | msg | a_nac | a_nac=>0 | msg |salida|
|2|"dame tu a??o de nacimeinto"| 2004 |si|"No puede ser 0"|No puede ser 0|
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
|1|"dame tu a??o de nacimeinto"| 2004 |"dame el a??o actual" | 2022|No|2022-2004 |18|
|   | msg | a_nac | msg| a_act |a_act=>0 |msg |
|2|"dame tu a??o de nacimeinto"| 2004 |"dame el a??o actual"| 2002 |  si| "el a??o actual no puede ser menor al a??o de nacimiento" |
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
| msg | n | n>0  | msg| v  |v>0   |  v%2==0  | c=c+1  | c<=n   | sp   |
| ----------- | ----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |
 | "cuantos numeros"|  4|no|"dame el numero",c,"de",n  | 5+1| no   |6 | no  |   | 6    |    
#### DIAGRAMA 18
![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%2018.png)

**PRUEBA DE ESCRITORIO**
|corridas| msg |num  |num>10 |msg |salida |
| ----------- | ----------- |----------- |----------- |----------- |----------- |
|1|"dame un numero en el teclado"| 5 | no|"es menor a 10"| es menor a 10|
|   | msg |num  |num>10 |msg |salida | 
|2|"dame un numero en el teclado"| 14 |si  |"es mayor a 10"| es mayor a 10|
#### DIAGRAMA 19
![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%2019.png)

**PRUEBA DE ESCRITORIO**
|corridas| num |num>10 |n=10-num |msg |salida |
| ----------- | ----------- |----------- |----------- |----------- |----------- |
|1|   5  | no   | 10-5 | "te falta",n,"para llegar a 10"| te falta 5 para llegar a 10  |
|   | num |num>10 |n=num-10 |msg |salida |
|2|  11  |   si  |  11-10    | "te pasaste por",n,"de 10"   | te pasaste por 1 de 10 |
#### DIAGRAMA 20
![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%2020.png)

**PRUEBA DE ESCRITORIO**
|  msg   | num     |  num==0     |  num>0      |   cp=cp++1     |  msg     | num  |num==0     |  num>0 |cn=cn++1 | msg   | num     |  num==0| "+",cp "-",cn     | salida    |
| ----------- | ----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |
|  "dame un numero entero,(0) para terminar"|  5  | no   |  si  | 0+1    |"dame un numero entero,(0) para terminar"|  -6   |  no   | no    | 0+1  |"dame un numero entero,(0) para terminar"|  0  |  si   |"+",1,"-",1  | +1,-1    |
#### DIAGRAMA 21
![](https://github.com/ICIROJAS/PARCIAL-ICI/blob/main/DIAGRAMA%2021.png)

**PRUEBA DE ESCRITORIO**
| msg | num  |n<0 | cont=cont+1|msg |num  |n=0 |num   |
| ----------- | ----------- |----------- |----------- |----------- |----------- |----------- |----------- |
| "dame un numero positivo o negativo,(0) para terminar"|  5  | no |0+1 | "dame un numero positivo o negativo,(0) para terminar" |0  | si | 5 |





