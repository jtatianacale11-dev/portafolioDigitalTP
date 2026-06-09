# 📘 Unidad 2
## 💻Unidad 2: Estructuras Algorítmicas de Control
 📚 *Comprender los principios de las estructuras condicionales y repetitivas en C, desarrollando el pensamiento lógico necesario para controlar el flujo de los programas y resolver problemas mediante algoritmos*

---

## 🎯Objetivos de la unidad 
### 🎯Estructuras Algorítmicas Condicionales

- ✅ Condicional simple: Si … Entonces (if)
- 🔀 Condicional doble: Si … Entonces, Sino … (if-esle)
- 📂 Condicional múltiple: En caso de … (swich/case)
- 🧩 Anidamiento de condicionales

### 🎯Estructuras Algorítmicas Repetitivas

- 🔁 Para (for)
- 🔄 Mientras (while)
- ⏳ Hacer … Mientras (do-while)
- 🧩 Anidamiento de bucles
 
----

## 🧩 **Temas Principales**

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

##   🔤*Estructuras repetitivas *
(tipos y sus estructura en diagrama de flujo y en
pseudocódigo)

- ### 🔁 Para (for)




- ### 🔄 Mientras (while)






- ### ⏳ Hacer … Mientras (do-while)





- ### 🧩 Anidamiento de bucles





##   🧩*Ejercicio con estructura condicional y repetitiva* (lenguaje dado en clase).


##  🗯️*Planteamiento de problema*


##  📝*Análisis del problema*


##  ✍️ *Diseño del algoritmo* 



##  💻*Codificación * (código fuente)




## 💡 *Validación* (prueba de escritorio)




# 📌*Principales dificultades y reflexión crítica en la aplicación de los contenidos.*





