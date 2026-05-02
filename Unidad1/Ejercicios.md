# 🔤EJERCICIO

🗯️Realice un programa que calcule la distancia de entre los puntos p1(x1,y1) y p2(x2,y2) considerando que
d= ((X2-X1)^2+(Y2-Y1)^2)^ 1⁄2

# 📝 Pseudocódigo
Algoritmo CalcularDistancia
		// Definición de variables
		Definir x1, y1, x2, y2, distancia Como Real
		
		Escribir "Calcular la distancia entre dos puntos p1,p2:"
		
		// Entrada de datos
		Escribir "Ingrese X1:"
		Leer x1
		Escribir "Ingrese X2:"
		Leer x2
		Escribir "Ingrese Y1:"
		Leer y1
		Escribir "Ingrese Y2:"
		Leer y2
		
		// Proceso: Usamos la fórmula de distancia
		// d = raíz((x1-x2)^2 + (y2-y1)^2)
    
		distancia <- raíz((x1 - x2)^2 + (y2 - y1)^2)
		
		// Salida (Formato limpio sin ceros innecesarios)
    
		Escribir "La distancia entre p1 (", x1, ", ", y1, ") y p2 (", x2, ", ", y2, ") es: ", distancia;

FinAlgoritmo



# 🧩Diagrama de flujo

<img width="650" height="692" alt="Captura de pantalla (86)" src="https://github.com/user-attachments/assets/9c119345-5a24-4b9a-aba4-cc8958128936" />



# 📝 Pruebas de Escritorio

| x1 | x2 | y1 | y2 | Operación ($d = \sqrt{(x_1-x_2)^2 + (y_2-y_1)^2}$) | Imprime (Pantalla) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| *3* | *8* | *6* | *4* | $d = \sqrt{(3-8)^2 + (4-6)^2}$ | p1(3, 6) y p2(8, 4) es: 5.38516 |
| *4* | *2* | *6* | *3* | $d = \sqrt{(4-2)^2 + (3-6)^2}$ | p1(4, 6) y p2(2, 3) es: 3.60555 |
| *1* | *5* | *1* | *4* | $d = \sqrt{(1-5)^2 + (4-1)^2}$ | p1(1, 1) y p2(5, 4) es: 5 |


# 💻Codigo en C
<img width="1366" height="653" alt="Captura de pantalla (87)" src="https://github.com/user-attachments/assets/36f17179-7b29-40eb-9b14-82e9222dabd3" />

  

# 💻Ejecución del Programa

<img width="1366" height="636" alt="Captura de pantalla (88)" src="https://github.com/user-attachments/assets/fe36c2a8-b8ed-464a-9a36-906abec4c91c" />

