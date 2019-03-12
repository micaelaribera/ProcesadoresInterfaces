
### INF-233: Procesadores e Interfaces
# Tarea #1

# Sistemas numéricos
### 1.	¿Cuál es la relación entre dígito, base y posición en el sistema binario? 

El sistema de numeración binario utiliza sólo dos dígitos, el cero (0) y el uno (1).
En una cifra binaria, cada dígito tiene distinto valor dependiendo de la posición que ocupe. El valor de cada posición es el de una potencia de base 2, elevada a un exponente igual a la posición del dígito menos uno. Se puede observar que, tal y como ocurría con el sistema decimal, la base de la potencia coincide con la cantidad de dígitos utilizados (2) para representar los números.
Existen diferentes sistemas numéricos , cada uno de ellos se identifica por su base .
Dígito: Un dígito en un sistema numérico es un símbolo que no es combinación de otros y que representa un entero positivo.
Base de un sistema numérico: La base de un sistema numérico es el número de dígitos diferentes usados en ese sistema.


### 2.	Para los siguientes números binarios, determina qué valor el dígito resaltado representa y escriba este valor como el producto del dígito y una potencia de 2. Tus respuestas deben estar en sistema decimal.

11011.012                     = 1 x 20 = 0
11011.012                      = 1x2-2 = 1/4
11011.012                      = 1 x 25 = 32
11011.012                      = 1 x 26 = 64
### 3.	Escribe el número binario 101.112 en un formato parecido al siguiente. Tu respuesta final debe estar en decimal.

101101101 = 1x 20 =0
                       1 x 22 = 4
                       1 x 23  =8
                        1 x 25 =32
                        1 x 26  = 64
                        1 x 28  = 256   ∑total =364.

### 4.	Convierte los siguientes números de 4 bits de binario a decimal.
01012 = 5
01112= 7
00112= 3
10012= 9
10112 =11
11112 =15
00002 =0
11012 =13
### 5.	Convierte los siguientes números de 8 bits de binario a decimal.
000101012 = 21
101101012 = 181
110100112 = 211
011010002 = 104
### 6.	Convierte los siguientes números de 16 bits de binario a decimal.
10110101 000101012 = 46357
01101000 110100112= 26835
### 7.	Determina si las siguientes afirmaciones son correctas:
10012  <  510   no,  10012 es mayor 
01112  =  11110   no ,  11110 es mayor
00112  >  210   correcto
10012  >  11012  no, 11012  es mayor
10112  =  1110    correcto
11112  =  1510   correcto
00002  <  010    no, son iguales
11012  >  10102   correcto
### 8.	Convierte los siguientes números a decimal. 
718  =57
7116 =113
DE016=3552
110118=4617
ABC16=2748
100116=4097
70.78=56.
A1.F16=161.
 
## Representación de números negativos y aritmética
### 9.	¿Qué significa complementar un número binario?

El complemento a uno de un número binario se define como el valor obtenido al invertir todos los bits en la representación binaria del número (intercambiando 0 por 1 y viceversa). Los complementos del número se componen como el negativo del número original, en algunas operaciones aritméticas. Dentro de una constante (de -1), el complemento a uno se comporta como el negativo del número original con adición binaria. Sin embargo, a diferencia del complemento a dos, estos números no han tenido un uso generalizado debido a problemas tales como el desplazamiento de -1, que negar cero da como resultado un patrón distinto de bit cero negativo, menos simplicidad con el préstamo aritmético, etc. 
Un sistema de complemento a uno o el complemento aritmético de uno es un sistema donde los números negativos están representados por el inverso de las representaciones binarias de sus correspondientes números positivos. En tal sistema, un número es negado (convertido de positivo a negativo o viceversa) calculando el complemento de los unos. Un sistema de numeración de complementos de N-bit sólo puede representar enteros en el rango  − (2N−1−1) a 2N−1−1 mientras que el Complemento a dos puede expresar −2N−1 a 2N−1−1.
El sistema de numeración binaria de complemento a uno se caracteriza por el complemento bit de cualquier valor entero que es el negativo aritmético del valor. Es decir, invertir todos los bits de un número (el complemento lógico) produce el mismo resultado que restar el valor de 0.
Muchas computadoras tempranas, incluyendo el CDC 6600, el LINC, el PDP-1 y el UNIVAC 1107, usaron la notación de complemento a uno. Los sucesores del CDC 6600 continuaron usando el complemento a uno hasta finales de la década de los 80, y los descendientes de UNIVAC 1107 (la serie UNIVAC 1100/2200) todavía lo hacen, pero la mayoría de las computadoras modernas usan el complemento a dos.

### 10.	Escribe el complemento de uno para los siguientes números binarios de 5 bits. 
010012 = 10110
010112 = 10100
001112 = 11000
000012  = 11110
