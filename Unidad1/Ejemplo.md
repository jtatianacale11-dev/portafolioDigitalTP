# 🧠 Ejemplo 1

📝Se requiere conocer la superficie de un triángulo en función de la base y la altura.

### ✅ Pseudocódigo

 Algoritmo areadTriangulo
	// base*altura /2
	Definir base Como Real
	Definir altura Como Real
	Definir area Como Real
	Escribir 'Ingrese la base'
	Leer base
	Escribir 'Ingrese la altura'
	Leer altura
	// proceso
	area <- (base*altura)/2
	// Salida
	Escribir ' Area es igual: ', area
FinAlgoritmo


### 🧩Diagrama de flujo

<img width="664" height="691" alt="Captura de pantalla (81)" src="https://github.com/user-attachments/assets/1a6fb170-2502-4260-b775-190989470560" />



### 📝 Pruebas de Escritorio

| Base | Altura | Proceso: area = (base * altura) / 2 | Imprime |
| :--- | :---   | :---                                | :---    |
| 6    | 10     | area = (6 * 10) / 2                 | 30      |
| 15.5 | 4.2    | area = (15.5 * 4.2) / 2             | 32.55   |
| 20   | 30     | area = (20 * 30) / 2                | 300     |



### 💻Codigo en C

# include <stdio.h>

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



### 💻Ejecución del Programa

<img width="1195" height="337" alt="image" src="https://github.com/user-attachments/assets/f2538772-4959-45f9-8939-4ab8a8517368" />



🛠️ Ejemplo  🏠 Unidad 1
