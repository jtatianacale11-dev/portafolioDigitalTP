# 🧠 Ejemplo 1
📝Calcular y visualizar la longitud de la circunferencia y el área de un círculo de radio dado.


# ✅ Pseudocódigo

Algoritmo  calcular_logitudArea
	//Variables
	Definir radio Como Real
	Definir logitud Como Real
	Definir  area Como Real
	
	//Entrada
	Escribir "Ingrese el radio del circulo:";
	Leer radio
	
	// Proceso 
	logitud = 2 * PI * radio;
	area = PI * radio ^ 2;
	
	//Salida
	Escribir "La logitud del radio del circulo es:", logitud;
	Escribir "El area del radio del circulo es:", area;
	
	
	
FinAlgoritmo

# 🧩Diagrama de flujo

<img width="827" height="665" alt="Captura de pantalla (84)" src="https://github.com/user-attachments/assets/1f815af1-f0b5-4f1b-9217-0c5dd8b873e1" />

# 📝 Pruebas de Escritorio

| Radio (r) | Longitud ($L = 2 \cdot \pi \cdot r$) | Área ($A = \pi \cdot r^2$) | Imprime (Pantalla) |
| :--- | :--- | :--- | :--- |
| *6* | $L = 2 \cdot \pi \cdot 6$ | $A = \pi \cdot 6^2$ | L: 38 / A: 113 |
| *8* | $L = 2 \cdot \pi \cdot 8$ | $A = \pi \cdot 8^2$ | L: 50 / A: 201 |
| *14* | $L = 2 \cdot \pi \cdot 14$ | $A = \pi \cdot 14^2$ | L: 88 / A: 616 |


# 💻Codigo en C

#include <stdio.h>

int main(){

float base,altura,area;

printf("Ingrese la base:");
scanf("%f",&base);

printf("Ingrese la altura:");
scanf("%f",&altura);

area =(base*altura)/2;

printf("Area es igual:%.2f\n",area);

return 0;
}

# 💻Ejecución del Programa
