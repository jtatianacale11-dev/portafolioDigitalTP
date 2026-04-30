# 📘 UNIDAD 1 — Fundamentos de la Programación en C  

> 🧭 *Comprender los principios básicos de la programación estructurada en C y desarrollar el pensamiento lógico necesario para resolver problemas mediante algoritmos.*

---

## 🎯 **Objetivos de la Unidad**
- 💡 Comprender los conceptos básicos del lenguaje C.  
- 🧠 Desarrollar el pensamiento lógico y estructurado.  
- 🧮 Identificar los tipos de datos, variables y operadores en C.  
- 🔤 Manipular cadenas de caracteres utilizando funciones basicas de la biblioteca estándar `<string.h>`.  

---
## 🧩 **Temas Principales**
## 1. 🧾 **Algoritmo**  
💬*Un algoritmo es una secuencia de pasos lógicos, ordenados y finitos que se siguen para resolver un problema o realizar una tarea específica. Es la base antes de escribir cualquier código en lenguajes como C, Java o Python.Para que un algoritmo sea  efectivo,debe cumplir con estas características:
      
  * 📌*Preciso: Cada paso debe estar claramente definido sin ambigüedades.*
  * 📌*Finito: Debe tener un inicio y un final (un número determinado de pasos).*
  * 📌*Definido: Si se sigue el mismo algoritmo varias veces con los mismos datos, siempre se debe obtener el mismo resultado.*
  
        
## 2. 🔢 **Pseudocódigo**  
   💬*El pseudocódigo es una forma de escribir los pasos de un algoritmo utilizando un lenguaje muy cercano al nuestro, pero                  siguiendo una estructura lógica similar a la de un lenguaje de programación real.Se le llama "pseudo" (falso) porque no es                código que una computadora pueda ejecutar directamente, sino que sirve para que los programadores diseñen la lógica de un                 programa antes de sentarse a escribirlo en un lenguaje complejo como C, Java o Python.  
- ✏️*Su función principal es facilitar la comprensión de un algoritmo.*
- ✏️*Fácil de leer y escribir: Se usan palabras clave como Inicio, Leer, Escribir, Si-Entonces o Mientras.*
- ✏️*Independiente del lenguaje: Un mismo pseudocódigo puede ser traducido después a cualquier lenguaje de programación.*
- ✏️*Estructurado: Aunque es flexible, mantiene una jerarquía (sangrías o identación) para mostrar qué instrucciones están dentro de otras.*
    
### 📝Ejemplo:
  <img width="695" height="422" alt="Captura de pantalla (72)" src="https://github.com/user-attachments/assets/03d33e15-6a51-458a-b9de-3b7a83b5c883" />

## 3. 🧠 **Driagrama de flujo**
 💬*Un diagrama de flujo es la representación gráfica de un algoritmo o de un proceso. Utiliza símbolos geométricos definidos para representar diferentes tipos de acciones, conectados por flechas que indican el orden o la "ruta" que sigue la información.*

 Sus símbolos principales y sus funciones

* 🔘*Óvalo (Inicio / Fin): Indica dónde empieza y dónde termina el proceso.*
* ▱ *Paralelogramo (Entrada / Salida): Se usa cuando el programa necesita pedir un dato al usuario (Leer) o mostrar un resultado en pantalla (Imprimir).*
* 🟦*Rectángulo (Proceso): Representa cualquier operación lógica o matemática (por ejemplo: Suma = A + B).*
* 🔶*Rombo (Decisión): Representa una condición. Tiene una entrada y dos salidas posibles: Sí o No (Verdadero o Falso).*
* ⬇️*Flechas (Líneas de flujo): Indican la dirección del proceso.*
  
### 📝Ejemplo:
<img width="854" height="686" alt="Captura de pantalla (73)" src="https://github.com/user-attachments/assets/fde0548f-951a-42ae-8fb5-bee56318042b" />

## 📝 Prubeas de escritorio
💬Es un proceso manual donde sigues paso a paso la lógica de tu algoritmo o diagrama de flujo con datos reales para verificar si el resultado es el correcto y ayudan a detectar errores en la lógica antes de pasar el código a la computadora.
| Base    | Altura   | area <- (base*altura)/2         | Imprime |
|---------|----------|---------------------------------|---------|
|    12   |    8     |  area =( 12*8)/2                |  48     |   
|     6   |    4     |  area =( 6*4)/2                 |  12     | 



##  💻Lenguajes de programación 
## *Lenguaje C*
<img width="157" height="135" alt="image" src="https://github.com/user-attachments/assets/87792649-c27e-4ff7-836a-18f064920512" />  
💬El lenguaje C es un lenguaje de programación de propósito general, desarrollado originalmente por Dennis Ritchie en los Laboratorios Bell. Se clasifica como un lenguaje de medio nivel, lo que significa que combina la capacidad de manipulación de hardware y gestión de memoria de bajo nivel (similar al lenguaje ensamblador) con estructuras de control y sintaxis legibles propias de los lenguajes de alto nivel.

####  *Características principales:*
* 🖊️ *Eficiencia y Rapidez: Al ser un lenguaje compilado, se traduce directamente a código máquina, lo que minimiza el consumo de recursos y maximiza la velocidad de ejecución.*
* 🖊️ *Portabilidad: El código escrito en C puede ser adaptado a diferentes arquitecturas de hardware con cambios mínimos.*
* 🖊️ *Control de Memoria: A diferencia de lenguajes modernos, C permite el uso de punteros, otorgando al programador el control total sobre la gestión de la memoria dinámica.*
* 🖊️ *Modularidad: Facilita la división de programas complejos en módulos o funciones independientes, mejorando la organización del código.*

## JAVA
<img width="179" height="198" alt="image" src="https://github.com/user-attachments/assets/f060fe03-9168-4481-8f97-22a9a0c0e2ce" />
💬Java es un lenguaje de programación de alto nivel y una plataforma informática ampliamente utilizada en el mundo del desarrollo de software. Fue creado originalmente por Sun Microsystems en 1995.

####  *Características Principales:*
* ✍️  *Orientado a Objetos (POO): Todo en Java se organiza en torno a "objetos" y "clases", lo que facilita la reutilización de código y la creación de sistemas complejos de forma ordenada.*
* ✍️  *Independencia de la Plataforma: Gracias a que el código se traduce a un formato intermedio llamado bytecode, funciona igual en Windows, Linux o macOS.*
* ✍️  *Seguro y Robusto: Cuenta con un sistema de gestión de memoria automático conocido como Garbage Collector (recolector de basura), que ayuda a prevenir errores comunes de programación y fugas de memoria.*
* ✍️  *Multihilo: Permite ejecutar varias tareas de forma simultánea dentro de un mismo programa, mejorando el rendimiento en aplicaciones interactivas.*

Para trabajar con Java, solemos escuchar tres siglas importantes:
*  *JDK (Java Development Kit): El kit de herramientas necesario para escribir y compilar programas.*
*  *JRE (Java Runtime Environment): El entorno necesario para ejecutar los programas ya creados.*
*  *JVM (Java Virtual Machine): El intérprete que traduce el código para que la computadora lo entienda.*


## Python
<img width="167" height="152" alt="image" src="https://github.com/user-attachments/assets/f04ed650-5084-4f2d-be12-960aa3a329ca" />

Python es un lenguaje de programación de alto nivel, interpretado y de propósito general que se ha convertido en uno de los más populares del mundo debido a su sintaxis clara y legible, muy cercana al lenguaje humano (inglés).
Fue creado por Guido van Rossum y lanzado en 1991. Su filosofía se centra en la legibilidad del código y en permitir que los desarrolladores expresen conceptos en menos líneas de código que en lenguajes como C++ o Java.

####  *Características Principales:*

* 🖋️ *Sintaxis Sencilla: No utiliza llaves {} para definir bloques de código, sino que emplea la sangría (indentación) obligatoria, lo que fuerza a escribir código limpio.*
* 🖋️ *Lenguaje Interpretado: El código se ejecuta línea por línea, lo que facilita enormemente la depuración y el aprendizaje.*
* 🖋️ *Multiplataforma: Puedes escribir un programa en una computadora y ejecutarlo en cualquier otra (Windows, Mac, Linux) sin cambios.*
* 🖋️ *Gran Ecosistema: Tiene una enorme cantidad de librerías y frameworks gratuitos que permiten hacer casi cualquier cosa sin empezar desde cero.*

## ✅ Programación por bloques
 💬La programación por bloques es una metodología visual que permite crear secuencias lógicas y algoritmos arrastrando y encajando piezas de colores, cada una con comandos específicos, sin necesidad de escribir código textual. Ideal para principiantes, esta técnica fomenta el pensamiento computacional, la resolución de problemas y la creatividad mediante interfaces lúdicas.

####  *Características Principales:*

*  *Enfoque en la Lógica: El usuario se concentra en qué quiere que haga el programa, no en cómo se escribe correctamente.*
*  *Visual y Atractivo: Al ser colorido y gráfico, es mucho más amigable para principiantes y niños.*
*  *Retroalimentación Instantánea: La mayoría de estas plataformas permiten ver el resultado de las acciones de inmediato (por ejemplo, mover un personaje en la pantalla).*
*  *Sin Errores de Escritura: Al no escribir texto, no hay fallos por errores ortográficos o de puntuación.*

#### *Existen diversas plataformas diseñadas bajo este esquema:*
1.	Scratch: La más famosa del mundo, desarrollada por el MIT. Ideal para crear historias interactivas y juegos.
2.	PSeInt (Modo Visual): Muy utilizado en entornos académicos para aprender pseudocódigo antes de pasar a lenguajes reales.
3.	App Inventor: Una herramienta de Google y el MIT para crear aplicaciones reales de Android uniendo bloques.
4.	Blockly: Una librería de Google que muchas otras aplicaciones usan para integrar este sistema de programación.
5.	Tinkercad (Codeblocks): Permite programar circuitos de Arduino o diseñar piezas en 3D mediante bloques.





 



# 🧰 **Ejercicio**
- 📝
- 💬   


