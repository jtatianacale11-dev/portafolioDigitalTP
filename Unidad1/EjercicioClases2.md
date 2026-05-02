# 💻*Programación en C* 
#### 📝 Problema
### 🧩 **Escribir un programa para convertir una medida dada en pies a sus equivalentes en: a) yardas; b) pulgadas; c) centímetros; y d) metro. (1 pie: 12 pulgadas, 1 yarda= 3 pies, 1 pulgada= 2.54 cm, 1 metro= 100 cm). Leer el número de pies e imprimir el número de yardas, pies, pulgadas, centímetros y metros.**

#### 🔤Pseudocódigo 

Algoritmo medida_pie
	
    // Variables
    DEFINIR pie, yardas, pulgadas, centimetros, metros COMO REAL
	
    // Entrada
	
    ESCRIBIR "Ingrese la medida en pie:"
    LEER pie
	
    // Proceso
	
    yardas <- pie / 3
    pulgadas <- pie * 12
    centimetros <- pulgadas * 2.54
    metros <- centimetros / 100
	
    // Salida
	
    ESCRIBIR "La medida de pie en yardas es: ", yardas
    ESCRIBIR "La medida de pie en pulgadas es: ", pulgadas
    ESCRIBIR "La medida de pie en centímetros es: ", centimetros
    ESCRIBIR "La medida de pie en metros es: ", metros


FinAlgoritmo

	

#### 🧩 Diagrama de Flujo

<img width="488" height="694" alt="Captura de pantalla (99)" src="https://github.com/user-attachments/assets/5f19f29b-c616-4ec6-a5f3-9ad514b43288" />




#### 📝 Pruebas de Escritorio

Pie | Yardas | Pulgadas | Centímetros | Metros | Imprime |
|:---:|:------:|:--------:|:-----------:|:------:|:--------|
| 35  | 11.67  | 420.00   | 1066.80     | 10.67  | Yardas: 11.67, Pulgadas: 420.00, Centímetros: 1066.80, Metros: 10.67 |
| 25  | 8.33   | 300.00   | 762.00      | 7.62   | Yardas: 8.33, Pulgadas: 300.00, Centímetros: 762.00, Metros: 7.62 |
| 37  | 12.33  | 444.00   | 1127.76     | 11.28  | Yardas: 12.33, Pulgadas: 444.00, Centímetros: 1127.76, Metros: 11.28 |

#### 💻Codgio en C

<

#### 💻Ejecución del Programa




🏠 [Unidad 1 ](Unidad1.md)
