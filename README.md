# Aplicación Angular de Gráfico en Tiempo Real con WebSocket Binario

Esta es una sencilla aplicación Angular que demuestra la visualización de datos en tiempo real utilizando WebSocket para datos binarios. La aplicación te permite enviar y recibir datos binarios y mostrarlos en un gráfico en tiempo real.
Este front-end debe usarse en conjunto con el back-end realizado en Spring Boot: [back-end](https://github.com/alvaro-salazar/binary-websocket)


## Introducción

WebSocket es un protocolo que permite la comunicación en tiempo real entre un cliente y un servidor. En esta aplicación, utilizamos WebSocket para establecer una conexión entre el cliente Angular y el servidor, lo que permite el intercambio en tiempo real de datos binarios. El servidor envía datos binarios simulados en forma de una onda senoidal al cliente, y el cliente los muestra en un gráfico en tiempo real.

## Características

- **Visualización de Datos en Tiempo Real:** La aplicación proporciona un gráfico en tiempo real que se actualiza a medida que se reciben datos binarios del servidor.
- **Comunicación WebSocket:** Establece una conexión WebSocket para recibir y enviar datos binarios al servidor.
- **Gráfico de Datos:** La aplicación utiliza la biblioteca Chart.js para crear y actualizar un gráfico en tiempo real para la visualización de datos.

## Instrucciones de Inicio

Sigue estos pasos para poner en funcionamiento la aplicación en tu máquina local:

1. **Clonar el Repositorio:** Comienza por clonar el repositorio en tu máquina local.

   ```shell
   git clone <url-del-repositorio>
2. Instalar Dependencias: Navega hasta el directorio del proyecto e instala las dependencias requeridas mediante npm.
``` shell
cd aplicacion-grafico-tiempo-real
npm install
```
3. Clone y ejecute el back-end realizado en Spring Boot. [back-end](https://github.com/alvaro-salazar/binary-websocket)

4. Ejecutar la Aplicación: Inicia el servidor de desarrollo Angular para lanzar la aplicación.

5. Acceder a la Aplicación: Una vez que el servidor esté en funcionamiento, abre tu navegador web y accede a la aplicación en http://localhost:4200.


## Uso
Al acceder a la aplicación, verás un gráfico en tiempo real con un botón "Enviar Datos Binarios".
Haz clic en el botón "Enviar Datos Binarios" para enviar datos binarios al servidor. Los datos recibidos se mostrarán en tiempo real en el gráfico.

## Tecnologías Utilizadas
- Angular: Un popular marco de aplicaciones web basado en TypeScript.
- WebSocket: Para la comunicación bidireccional en tiempo real.
- Chart.js: Una biblioteca JavaScript para crear gráficos interactivos.

## Contribución
¡Las contribuciones son bienvenidas! Si deseas mejorar la aplicación o corregir problemas, sigue estos pasos:

## Haz un fork del repositorio.
1. Crea una nueva rama para tu función o corrección.
2. Realiza tus cambios y regístralos.
3. Crea una solicitud de extracción hacia la rama main.

## Licencia
Esta aplicación es de código abierto y está disponible bajo la Licencia MIT.
