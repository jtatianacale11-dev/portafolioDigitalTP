#  💻*Programación en C* 
## 🔤EJERCICIO

🗯️En una concesionaria de vehículos se realizaron tres ventas de vehículos de alta gama a 3 clientes. Cada vehículo cuesta 30000, 29000 y 33000 usd. El gerente desea saber cuál es porcentaje (comisión) que cada vendedor se llevaría, lo que le pagará a cada uno de ellos (considerando el 4% por cada vendedor) y lo que le pagará en conjunto (total).


# 📝 Pseudocódigo
Algoritmo comisiones_Concesionaria

		// Definir las ventas como constantes o variables
		Definir venta1, venta2, venta3 Como Real
		Definir comision1, comision2, comision3 Como Real
		Definir totalComisiones Como Real
		Definir PORCENTAJE_COMISION Como Real
		
		// Inicializar valores
		venta1 = 30000
		venta2 = 29000
		venta3 = 33000
		PORCENTAJE_COMISION <- 0.04 // Representa el 4%
		
		// Proceso: Calcular comisiones individuales
		comision1 = venta1 * PORCENTAJE_COMISION
		comision2 = venta2 * PORCENTAJE_COMISION
		comision3 = venta3 * PORCENTAJE_COMISION
		
		// Calcular el total que pagará la empresa en conjunto
		totalComisiones <- comision1 + comision2 + comision3
		
		// Salida de resultados
		Escribir "Comisión vendedor 1 (Venta 30000): ", comision1, " USD"
		Escribir "Comisión vendedor 2 (Venta 29000): ", comision2, " USD"
		Escribir "Comisión vendedor 3 (Venta 33000): ", comision3, " USD"
		Escribir "--------------------------------------------"
		Escribir "El pago total en comisiones es: ", totalComisiones, " USD"

FinAlgoritmo


# 🧩Diagrama de flujo

<img width="752" height="695" alt="Captura de pantalla (89)" src="https://github.com/user-attachments/assets/f8469b82-a048-4d84-9caf-91e83a53e118" />


# 📊 Pruebas de Escritorio

| Variable | Descripción | Operación / Proceso | Resultado |
| :---     | :---        | :---                | :---      |
| venta1   | Venta Vehículo A | Valor constante | *30,000* |
| venta2   | Venta Vehículo B | Valor constante | *29,000* |
| venta3   | Venta Vehículo C | Valor constante | *33,000* |
| tasa     | Porcentaje Comisión | $4 / 100$ | *0.04* |
| comision1 | Pago Vendedor 1 | $30,000 \times 0.04$ | *1,200* |
| comision2 | Pago Vendedor 2 | $29,000 \times 0.04$ | *1,160* |
| comision3 | Pago Vendedor 3 | $33,000 \times 0.04$ | *1,320* |
| *total* | *Gasto Total Empresa* | $1,200 + 1,160 + 1,320$ | *3,680* |


# 💻Codigo en C

<img width="1366" height="695" alt="Captura de pantalla (90)" src="https://github.com/user-attachments/assets/e77bf943-2180-4748-97cd-f78530f0f22b" />



# 💻Ejecución del Programa

<img width="1366" height="649" alt="Captura de pantalla (91)" src="https://github.com/user-attachments/assets/db1331cb-8bbd-4339-8729-12039a8c4d3e" />


[Unidad 1](Unidad1.md)
