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
   git clone https://github.com/tu-usuario/Conversos-De-Divisas.git

## Con maven

   ```maven
   <dependency>
    <groupId>com.google.code.gson</groupId>
    <artifactId>gson</artifactId>
    <version>2.8.9</version>
</dependency>
```

1. Regístrate en ExchangeRate API para obtener tu clave de API.
2. Configura tu clave de API en el código (por ejemplo, como una constante o variable de entorno).
3. Ejecuta el proyecto.

## Uso

1. Ingresa la moneda de origen y la moneda de destino.
2. Especifica la cantidad a convertir.
3. El sistema hará una solicitud a la API, procesará la respuesta y mostrará el resultado en la interfaz.
