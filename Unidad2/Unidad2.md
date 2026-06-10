# 📘 Unidad 2
## 💻Unidad 2: Estructuras Algorítmicas de Control
 📚 *Comprender los principios de las estructuras condicionales y repetitivas en C, desarrollando el pensamiento lógico necesario para controlar el flujo de los programas y resolver problemas mediante algoritmos*
 
----

##   🧮*Estructuras condicionales*

- ### ✅ Condicional simple: Si … Entonces (if)
Es una estructura de control que permite al programa tomar una decisión: ejecutar un bloque de código solo si se cumple una condición específica (es decir, si el resultado de la condición es verdadero).
Si la condición es falsa, el programa simplemente ignora ese bloque y continúa con la siguiente instrucción.

#### Estructura en diagrama de flujo

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/668663de-cbe9-4bb2-a2da-26f10857dcb1" />


#### Pseudocódigo

Algoritmo notaUnidad

    Definir nota Como Real
    
    // Entrada de datos
    Escribir "Ingrese la nota:"
    Leer nota
    
    // Estructura Condicional Simple 
    Si nota >= 7 Entonces
        Escribir "¡Felicidades, has aprobado!"
    FinSi
    
FinAlgoritmo
----


- ### 🔀 Condicional doble: Si … Entonces, Sino … (if-esle)
El if else es una estructura condicional que permite evaluar una condición y ejecutar una acción si es verdadera, o una acción diferente si es falsa. Se utiliza cuando existen dos posibles resultados para una misma situación.

#### Estructura en diagrama de flujo

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/30de90cf-664f-4774-9049-0f139f21b2ae" />


#### Pseudocódigo

Algoritmo notaUnidadDoble

    Definir nota Como Real
    
    // Entrada de datos
    Escribir "Ingrese la nota:"
    Leer nota
    
    // Estructura Condicional Doble
    Si nota >= 7 Entonces
        Escribir "¡Felicidades, has aprobado!"
    Sino
        Escribir "Lo siento, has reprobado la unidad."
    FinSi
    
FinAlgoritmo

-----

 - ### 📂 Condicional múltiple: En caso de … (swich/case)
La estructura condicional múltiple permite evaluar varias opciones y ejecutar una acción diferente para cada una. Se utiliza cuando existen más de dos posibles resultados. Por ejemplo, se puede usar para mostrar el día de la semana según el número que ingrese el usuario. Esta estructura ayuda a organizar mejor el programa cuando hay muchas alternativas que evaluar.

#### Estructura en diagrama de flujo


<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/6ede4fb7-2527-40da-8d98-c34341e74b42" />


#### Pseudocódigo

Este programa pide un número al usuario y muestra el nombre del mes correspondiente. Si el número no está entre las opciones disponibles, indica que el mes no es válido. Se utiliza una estructura condicional múltiple porque existen varias alternativas posibles según el dato ingresado.


Algoritmo MesesDelAnio

	
    Definir mes Como Entero
	
    Escribir "Ingrese un número del 1 al 4:"
    Leer mes
	
    Segun mes Hacer
        1:
            Escribir "Enero"
        2:
            Escribir "Febrero"
        3:
            Escribir "Marzo"
        4:
            Escribir "Abril"
        De Otro Modo:
            Escribir "Mes no válido"
    FinSegun
	
FinAlgoritmo


-----


- ### 🧩 Anidamiento de condicionales

Es una estructura en la que una condición se encuentra dentro de otra condición. Se utiliza cuando es necesario realizar una segunda verificación después de que se cumple o no una primera condición. Esto permite tomar decisiones más específicas dentro de un programa.


#### Estructura en diagrama de flujo

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/dcf3db33-37dc-4e6d-9784-51796732d1da" />



#### Pseudocódigo

Este programa solicita una nota al usuario. Primero verifica si la nota es mayor o igual a 7. Si se cumple, realiza una segunda condición para comprobar si la nota es mayor o igual a 9. Si lo es, muestra “Excelente”; de lo contrario, muestra “Aprobado”. Si la nota es menor a 7, muestra “Reprobado”. Es una estructura condicional anidada porque una condición está dentro de otra.


Algoritmo NotaAnidada
	
    Definir nota Como Entero
	
    Escribir "Ingrese la nota:"
    Leer nota
	
    Si nota >= 7 Entonces
        Si nota >= 9 Entonces
            Escribir "Excelente"
        Sino
            Escribir "Aprobado"
        FinSi
    Sino
        Escribir "Reprobado"
    FinSi
	
FinAlgoritmo


-----

##   🔤Estructuras repetitivas 

- ### 🔄 Mientras (while)
La estructura while se utiliza cuando no se sabe exactamente cuántas veces se repetirá una acción. El ciclo continúa ejecutándose mientras la condición sea verdadera y se detiene cuando la condición se vuelve falsa.

#### Estructura en diagrama de flujo


<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/030d2b9c-1a4f-4752-b03b-a5e141863b3d" />



#### Pseudocódigo

Este programa utiliza la estructura repetitiva while para mostrar la tabla de multiplicar del 2. El ciclo comienza con i = 1 y se repite mientras i sea menor o igual a 10. En cada repetición se muestra una operación de la tabla y luego se incrementa el valor de i en 1. Cuando i supera 10, el ciclo termina.

Algoritmo TablaDelDos
	
    Definir i Como Entero
    i <- 1
	
    Mientras i <= 10 Hacer
        Escribir "2 x ", i, " = ", 2 * i
        i <- i + 1
    FinMientras
	
FinAlgoritmo


------


- ### ⏳ Hacer … Mientras (do-while)

La estructura repetitiva do-while es un ciclo que ejecuta un conjunto de instrucciones al menos una vez y luego verifica una condición. Si la condición es verdadera, el ciclo continúa repitiéndose; si es falsa, termina. Su principal característica es que la condición se evalúa al final del ciclo

#### Estructura en diagrama de flujo

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/32c51a3e-43f0-4437-82cb-5f0a7c3896b8" />


#### Pseudocódigo

Este programa utiliza la estructura repetitiva do-while para mostrar los números del 1 al 3. Primero muestra el valor de la variable i, luego la incrementa en 1 y finalmente verifica si i es mayor que 3. Mientras no lo sea, el ciclo continúa repitiéndose. Cuando i supera 3, el programa termina.


Algoritmo ContarHasta3
	
    Definir i Como Entero
	
    i <- 1
	
    Repetir
        Escribir i
        i <- i + 1
    Hasta Que i > 3
	
FinAlgoritmo

-----

- ### 🔁 Para (for)
  
La estructura repetitiva for se utiliza cuando se conoce la cantidad de veces que se desea repetir una acción. Permite controlar el inicio, la condición y el incremento de una variable.

#### Estructura en diagrama de flujo

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/b58d62c3-c539-46b0-a3ca-44229b224883" />


#### Pseudocódigo

Elaborar un programa que muestre la tabla de multiplicar del número 5 desde 5 × 1 hasta 5 × 10 utilizando la estructura repetitiva for.

Algoritmo TablaDelCinco
	
    Definir i Como Entero
	
    Para i <- 1 Hasta 10 Hacer
        Escribir "5 x ", i, " = ", 5 * i
    FinPara
	
FinAlgoritmo


----

- ### 🧩 Anidamiento de bucles
El anidamiento de bucles consiste en colocar un ciclo dentro de otro ciclo. Se utiliza cuando se necesita realizar varias repeticiones dentro de cada repetición de otro ciclo. Es muy útil para trabajar con tablas, filas y columnas.


#### Estructura en diagrama de flujo


<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/df41896a-04a9-4b0d-99b6-745560fbe6f8" />


#### Pseudocódigo
Mostrar las tablas de multiplicar del 1 al 3.

Algoritmo TablasMultiplicar 
	
    Definir i, j Como Entero
	
    Para i <- 1 Hasta 3 Hacer
        Escribir "Tabla del ", i
		
        Para j <- 1 Hasta 5 Hacer
            Escribir i, " x ", j, " = ", i * j
        FinPara
		
    FinPara
	
FinAlgoritmo


-----

##   🧩*Ejercicio con estructura condicional y repetitiva*

###  🗯️*Planteamiento de problema*

Ejemplo: Ingresar un número comprendido entre 10 a 20 y guardarlo en una variable N. Luego imprimir de manera decreciente la serie de todos los números desde N hasta cero (0) y además mostrar la suma de todos estos números de la serie. 

Ejemplo: Se ingresa el número 11, entonces en pantalla mostrar: “11, 10, 9, 8, .... ,0” y luego mostrar el resultado de la suma de 11+10+9+8+...+0=66.



###   📝*Análisis del problema*

| Etapa    |   Enfoque      | Implementación        | 
|---------|----------|---------------------------------|
|    ENTRADA   |    Implementé un filtro para evitar errores de usuario, validando que el número esté dentro del rango entre 10-20   |  Usé un ciclo ⁠do-while⁠ que obliga a repetir la solicitud mientras el dato no cumpla la condición. |    
|     PROCESO  | Diseñé un ciclo para recorrer la serie y realizar la sumatoria acumulativa        |  Utilicé un ⁠for⁠ que decrementa desde N hasta 0, sumando el valor de ⁠j⁠ en cada iteración.                |  
|    SALIDA  |    Mostré la serie paso a paso para verificar el funcionamiento y luego el resultado final     |  Imprimí cada valor de ⁠j⁠ durante el bucle y presenté el valor total almacenado en ⁠Suma⁠.                 |  



###   ✍️ *Diseño del algoritmo* 


<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/d5ddd2a8-0fd0-4802-a239-657597585074" />



### 💻*Codificación * 


<img width="1366" height="671" alt="Captura de pantalla (176)" src="https://github.com/user-attachments/assets/24e446ec-763c-41b1-8838-5333ffe4a6e5" />



<img width="1366" height="504" alt="Captura de pantalla (177)" src="https://github.com/user-attachments/assets/6cc7dd8d-cd6d-45ce-9dc8-314d3f61f95e" />



###  💡 *Validación* 

| Iteracion (j)    | Suma(Inicio:0)   | Suma + j        | Imprime |
|---------|----------|---------------------------------|---------|
|    11   |    0     |  0+11             |  11    |   
|    10   |    11     |  11+ 10                |  21    | 
|    9   |    21    |  21+ 9                |  30   |
|    8   |    30    |  30+ 8                |  38   | 
|    7   |    38    |  38+ 7                |  45   | 
|    6   |    45    |  45+ 6                |  51   | 
|    5   |    51    |  51+ 5                |  56   | 
|    4   |    56    |  56+ 4                |  60   | 
|    3   |    60    |  60+ 3                |  63   | 
|    2   |    63    |  63+ 2                |  65   | 
|    1   |    65    |  65+ 1                |  66   | 
|    0   |    66    |  66+ 0                |  66   | 


## 📌*Principales dificultades y reflexión crítica en la aplicación de los contenidos.*

La mayor dificultad encontrada fue comprender la diferencia entre la estructura de control de validación (⁠do-while⁠) y la estructura de iteración (⁠for⁠). Inicialmente, el diagrama de flujo no acumulaba correctamente el valor de ⁠j⁠ en ⁠Suma⁠, lo que resultó en resultados erróneos. Mediante la depuración y la comparación del pseudocódigo con la sintaxis de C, logré entender que la variable acumuladora debe actualizarse con el valor de la variable de control (⁠Suma += j⁠) en cada iteración del bucle



