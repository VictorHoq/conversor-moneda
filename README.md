# Conversor de Moneda 💱

Un simple conversor de moneda desarrollado en **Java**. Permite convertir entre diferentes monedas de forma rápida y sencilla utilizando la API de **exchangerate-api**.


## Descripción
Este proyecto es una herramienta que facilita la conversión de divisas en tiempo real. Realiza consultas a la API de **exchangerate-api** para obtener los tipos de cambio actualizados.

## Características
- Conversión entre múltiples monedas.
- Consultas en tiempo real a exchangerate-api.
- Interfaz de línea de comandos sencilla.
- Validación de entradas.

## Instalación
1. Clona este repositorio:
   ```bash
   git clone https://github.com/VictorHoq/conversor-moneda.git
   ```
2. Accede al directorio del proyecto:
   ```bash
   cd conversor-moneda
   ```
3. Compila el proyecto:
   ```bash
   javac ConversorMoneda.java
   ```
4. Ejecuta el proyecto:
   ```bash
   java ConversorMoneda
   ```

## Uso
1. Ingresa la cantidad a convertir.
2. Selecciona la moneda de origen y destino.
3. El programa realizará una consulta a exchangerate-api y mostrará el resultado de la conversión.