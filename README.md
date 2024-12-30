# Conversor de Monedas

Este proyecto es una aplicación desarrollada en **Java** que permite convertir entre distintas monedas utilizando una API de tasas de cambio actualizadas. La aplicación hace uso de la biblioteca **Gson** para procesar y transformar los datos recibidos de la API.

## Características

- Conversión entre monedas específicas (detalladas más abajo).
- Datos actualizados en tiempo real gracias a una API de tasas de cambio.
- Interfaz sencilla y fácil de usar.
- Manejo eficiente de datos en formato JSON con Gson.

## Monedas Soportadas

Actualmente, la aplicación permite convertir entre las siguientes monedas, todas hacia y desde el dólar estadounidense (USD):

- **Peso argentino (ARS)**  
- **Peso colombiano (COP)**  
- **Real brasileño (BRL)**  

Puedes realizar conversiones como:  
- De USD a ARS  
- De ARS a USD  
- De USD a COP  
- De COP a USD  
- De USD a BRL  
- De BRL a USD  

## Requisitos del Sistema

- **Java** 8 o superior.
- Biblioteca externa: **Gson**.
- Conexión a Internet para acceder a la API.

## Instalación y Ejecución

1. Clona este repositorio en tu máquina local:

   ```bash
   git clone https://github.com/tu-usuario/conversor-monedas.git
