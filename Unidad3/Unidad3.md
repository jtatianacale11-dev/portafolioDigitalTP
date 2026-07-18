# 📘 Unidad 3: Programación Modular y Estructuras de Datos Estáticas

> 📚 **Modularidad **
---

# Programación Modular

## 📦 Conceptos básico de programación modular

La modularidad es un principio de la programación que consiste en dividir un programa en partes más pequeñas llamadas módulos, funciones o procedimientos. 
Cada módulo se encarga de resolver una tarea específica y esto ofrece varias ventajas: facilita la lectura del código, permite reutilizar funciones sin tener que reescribirlas y hace que sea mucho más sencillo encontrar y corregir errores.

---

## 🧩 Paso de parámetros por valor

En el paso por valor, la función recibe únicamente una copia local de los datos que le envías.

- ¿Cómo funciona internamente?: Cuando se llama a la función, el sistema reserva un nuevo espacio en la memoria para las variables de la función (parámetros formales) y copia los datos de las variables originales en esos nuevos espacios.

-Aislamiento total: Existe una barrera absoluta entre la función y el programa principal. Cualquier modificación, cálculo o reasignación que sufra la variable dentro de la función muere cuando la función termina.

-¿Cuándo se usa?: Es el método por defecto cuando solo necesitas leer la información de una variable para realizar un cálculo (por ejemplo, calcular el IVA de un precio), asegurándote de que el valor original no sufra alteraciones accidentales.

---

### 🛠️Ejemplo:

- <img width="800" height="690" alt="Captura de pantalla (472)" src="https://github.com/user-attachments/assets/59d637d3-2c9d-4103-9ffd-3a8f2ed3c441" />



### 📊 Paso de parámetros por referencia (con punteros)

> **Definición:**
 En el paso por referencia, la función no recibe una copia, sino el acceso directo a la variable original.

-¿Cómo funciona internamente?: En lugar de duplicar los datos en memoria, lo que se le pasa a la función es la dirección de memoria (el "puntero" o enlace) de la variable original. La variable dentro de la función se convierte en un alias o un "nombre alternativo" para la misma casilla de memoria externa.

Modificación directa: No hay duplicación de datos. Si la función cambia el valor de ese parámetro, está alterando directamente la memoria de la variable original del programa principal. El cambio persiste después de que la función finaliza.

En la función: Usamos un asterisco * en el parámetro para decirle a C que vamos a recibir una dirección de memoria (un puntero).

En el main: Usamos el ampersand & al llamar a la función para enviarle la dirección de memoria exacta de nuestra variable (tal como haces dentro del scanf).


#### 🧠 Ejemplo:
<img width="993" height="708" alt="Captura de pantalla (471)" src="https://github.com/user-attachments/assets/ec44d2fb-00e1-465c-b3e9-cf99207e3a50" />




## ⬛ Arreglos 

### 



### Bidimensionales (Matrices)
📝 Estructura que organiza datos en dos dimensiones: filas y columnas. 
🧾 Conocidos comúnmente como matrices o tablas. 
🔀 Funcionamiento: Similar a una hoja de cálculo o una sala de cine (Fila F, Asiento 5). 
💡 Uso: Ideales para tableros de juego, mapas o relaciones matemáticas.

Estructura básica:

C
int tablero[3][3];
✅ Características:

🔀 Acceso: Se usa la sintaxis matriz[i][j].

🏗️ Memoria: Se guardan linealmente en memoria, fila tras fila.

📖 Recorrido: Usualmente requiere dos ciclos for anidados.

🧠 Diagrama de Flujo


📌 Codigo en C

<img width="459" height="257" alt="image" src="https://github.com/user-attachments/assets/0d64fe6c-77be-445f-a008-b7dda726b18a" />

---

### 📦 Arreglos Multidimensionales
✅ : Arreglos con tres o más dimensiones. 
☑️ Es una extensión lógica de las matrices. 
💡 Analogía: Si una matriz es una hoja, un arreglo 3D es un libro (muchas hojas), o un edificio.

Estructura básica:

C
int cubo[3][3][3];
✅ Características:

🔀 Requiere un índice por cada dimensión.

🏗️ El consumo de memoria crece exponencialmente.

🗂️ Requiere alta abstracción lógica.



📌 Codigo en C

<img width="459" height="257" alt="image" src="https://github.com/user-attachments/assets/c2628068-5253-4180-9eec-5dbad6c0a28d" />

---

### 🔤 Cadenas o Strings
✅ En C, es un arreglo de caracteres (char) diseñado para almacenar texto. 
☑️ No existe un tipo primitivo "String", es un arreglo especial.
---

### ⚠️ Principales Dificultades

> ✔️ Mi mayor dificultad es olvidar que los arreglos inician en 0. 

> ✔️ Me cuesta visualizar arreglos de más de 2 dimensiones.

> ✔️  A veces confundo el paso por valor y por referencia.
> 
### 🌀 Reflexión crítica

> *🗂️ La transición a estructuras de datos y modularidad marca un antes y un después en mi lógica. Entiendo que dividir un problema en funciones hace que sea más fácil de resolver y mantener. Reconozco que dominar los arreglos es fundamental para bases de datos futuras. Necesito practicar más el 'dibujar' el problema en papel antes de codificar.*



[Portafolio](portafolio.md)
