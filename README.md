# Laboratorio-N9
## Integrantes: Gaona Carlos, Masaquiza Alex, Morillo Ariel
## NRC: 5407

**1. OBJETIVOS**

_Objetivo General_

- Analizar los problemas en el dominio de los fasores usando algebra compleja.

_Objetivos Específicos_

- Comprender la forma de representar de forma rectangular a polar y viceversa los diferentes problemas

- Verificar los resultados al aplicar todas las operaciones basicas de numeros complejos tales como la suma, resta, multiplicacion y division.

- Comparar las respuestas conseguidas analiticamente con los de una calculadora cientifica.

**2. MARCO TEÓRICO**

![1](https://github.com/AlexMP98/Laboratorio-N9/blob/main/Imagenes/1.PNG) 

![2](https://github.com/AlexMP98/Laboratorio-N9/blob/main/Imagenes/2.PNG) 

**3. EXPLICACIÓN DEL PROCEDIMIENTO**

_**CONVERSIÓN DE FORMA RECTANGULAR A FORMA POLAR**_

El primer paso para convertir de forma rectangular a forma polar es determinar la magnitud del fasor.

Un fasor puede ser visualizado como formando parte de un triángulo rectángulo en el plano complejo, según indica la figura, para cada ubicación en los cuadrantes. El lado horizontal del triángulo es el valor real A, y el lado vertical es el valor j, B. La hipotenusa del triángulo es la longitud del fasor C, la cual representa la magnitud y puede ser expresada, con el teorema de Pitágoras, como:

![RP1](https://github.com/AlexMP98/Laboratorio-N9/blob/main/Imagenes/RP1.png)

A continuación, el ángulo θ indicado en las partes (a) y (b) de la figura se expresa como una función tangente inversa:

![RP2](https://github.com/AlexMP98/Laboratorio-N9/blob/main/Imagenes/RP2.png)

El ángulo θ indicado en las partes (b) y (c) de la figura es:

![RP3](https://github.com/AlexMP98/Laboratorio-N9/blob/main/Imagenes/RP3.png)

El cual incluye ambas condiciones tal como señalan los signos duales:

![RP4](https://github.com/AlexMP98/Laboratorio-N9/blob/main/Imagenes/RP4.png)

En cada caso deben utilizarse los signos apropiados en el cálculo. La fórmula general para convertir de forma rectangular a forma polar es:

![RP5](https://github.com/AlexMP98/Laboratorio-N9/blob/main/Imagenes/RP5.png)


_**CONVERSIÓN DE FORMA POLAR A FORMA RECTANGULAR**_

La forma polar proporciona la magnitud y el ángulo de una cantidad fasorial, como se indica en la figura.

![PR1](https://github.com/AlexMP98/Laboratorio-N9/blob/main/Imagenes/PR1.png)

Para obtener la forma rectangular, se deben encontrar los lados A y B del triángulo utilizando las reglas de trigonometría expresadas a continuación:

![PR2](https://github.com/AlexMP98/Laboratorio-N9/blob/main/Imagenes/PR2.png)

La fórmula de conversión de polar a rectangular es:

![PR3](https://github.com/AlexMP98/Laboratorio-N9/blob/main/Imagenes/PR3.png)


_**OPERACIONES MATEMÁTICAS**_

**Adición**

Los números complejos deben estar en forma rectangular para poder sumarlos. La regla es:
-	Sumar las partes reales de cada número complejo para obtener la parte real de la suma.
-	 A continuación, se suman las partes j de cada número complejo para obtener la parte j de la suma.

**Sustracción**

Igual que en la adición, los números deben estar en forma rectangular para poder restarlos. La regla es:
-	Restar las partes reales de los números para obtener la parte real de la diferencia.
-	A continuación restar las partes j de los números para obtener la parte j de la diferencia.

**Multiplicación**

La multiplicación de dos números complejos en forma rectangular se realiza multiplicando, en su oportunidad, cada término de un número por ambos términos del otro y combinando luego los términos reales resultantes y los términos j resultantes (recuerde que j * j = -1). Como un ejemplo:

![OM](https://github.com/AlexMP98/Laboratorio-N9/blob/main/Imagenes/OM.png)

La multiplicación de dos números complejos es más fácil cuando ambos están en forma polar, por lo que es mejor convertirlos a forma polar antes de multiplicarlos. La regla es:
-	 Multiplicar las magnitudes, y sumar los ángulos algebraicamente.

**División**

La división de dos números complejos en forma rectangular se logra multiplicando tanto el numerador como el denominador por el complejo conjugado del denominador y combinando luego los términos para finalmente simplificar. El complejo conjugado de un número se encuentra cambiando el signo del término j. Como un ejemplo:

![OD](https://github.com/AlexMP98/Laboratorio-N9/blob/main/Imagenes/OD.png)

Igual que la multiplicación, la división es más fácil cuando los números están en forma polar, por lo que es mejor convertirlos a forma polar antes de dividirlos. La regla es:
-	 Dividir la magnitud del numerador entre la magnitud del denominador para obtener la magnitud del cociente.
-	 Restar a continuación el ángulo del denominador del ángulo del numerador para obtener el ángulo del cociente.



**4. RESPUESTAS A INTERROGANTES Y CALCULO DE ERROR**     
4.1 Transforme a su forma polar:     
![1](https://github.com/AlexMP98/Laboratorio-N9/blob/main/Imagenes/1.png)     
     
4.2 Transforme a su forma rectangular:      
![2](https://github.com/AlexMP98/Laboratorio-N9/blob/main/Imagenes/2.png)    

4.3 Realice las siguientes operaciones paso a paso, y represente el resultado tanto en su forma rectangular como en su forma polar:     
![3_a](https://github.com/AlexMP98/Laboratorio-N9/blob/main/Imagenes/3_a.png)       
![3_b](https://github.com/AlexMP98/Laboratorio-N9/blob/main/Imagenes/3_b.png)        
![3_c](https://github.com/AlexMP98/Laboratorio-N9/blob/main/Imagenes/3_c.png)    

4.4 Resuelva las operaciones anteriores por medio de la calculadora y compare los resultados:      
![4](https://github.com/AlexMP98/Laboratorio-N9/blob/main/Imagenes/4.png)       

Como se puede observar los resultados obtenidos analíticamente son muy parecidos a los resultados obtenidos por la calculadora científica, la diferencia es de décimas y esto se debe a que al momento de trabajar analíticamente se usan solo dos décimas para los cálculos mientras que la calculadora arroja un valor más exacto ya que trabajo con todas las décimas.




**5. VIDEO**          

Link del video: https://youtu.be/i79qxZrUPD8




**6. CONCLUSIONES**

- Trabajar con complejos complica los detalles de calculo,no altera los principios basicos de los problemas y circuitos.

- Con el enfoque de fasores, el analisis de circuitos de ca se maneja de forma similar al analisis de circuitos de cd, y todas las relaciones basicas y teoremas se aplican.

- La suma y resta de numeros complejos se puede realizar mejor en forma rectangular mientras que la multiplicacion y division es mas factible hacerlo de forma polar. 

**7. BIBLIOGRAFÍA**     
H. Robbins, A. y Wilhem C. Miller. (2008). Análisis de circuitos: teoría y prática,Cuarta Edición. Ciudad de México: CENGAGE Learning.



