# Conexión ESPCAM por WebSocket y Deploy en Heroku Cloud 📷🔌

Este proyecto consiste en establecer una conexión WebSocket entre una ESPCAM (cámara ESP32 con soporte para cámara OV2640) y un servidor en la nube Heroku. La ESPCAM enviará transmisiones de video en tiempo real al servidor Heroku, donde se podrán visualizar a través de una interfaz web.

## Características 🛠️

- **Transmisión de Video en Tiempo Real:** La ESPCAM captura imágenes de la cámara OV2640 y las transmite en tiempo real a través de una conexión WebSocket al servidor Heroku.

- **Despliegue en Heroku:** El servidor en la nube Heroku actúa como intermediario entre la ESPCAM y los clientes web, permitiendo la visualización remota de las transmisiones de video.

- **Interfaz Web Responsiva:** Los clientes web pueden acceder a una interfaz web responsiva para visualizar el video en tiempo real desde la ESPCAM, con capacidad para adaptarse a diferentes dispositivos y tamaños de pantalla.

## Componentes Necesarios 📦

- ESPCAM (ESP32 con cámara OV2640)
- Conexión a Internet (WiFi o Ethernet) para la ESPCAM
- Cuenta en Heroku para el despliegue del servidor en la nube

## Instrucciones de Uso 📝

1. **Configuración de la ESPCAM:** Carga el código en la ESPCAM para iniciar la captura de video y establecer una conexión WebSocket con el servidor Heroku.

2. **Despliegue en Heroku:** Despliega el servidor proporcionado en este repositorio en tu cuenta de Heroku.

3. **Acceso a la Interfaz Web:** Una vez desplegado el servidor en Heroku, accede a la URL proporcionada para visualizar el video en tiempo real desde la ESPCAM.

## Ejemplo de Interfaz 📋

![Interfaz de la Web App](web_app.png)

## Contribuciones 🚀

¡Contribuciones son bienvenidas! Si tienes ideas para mejorar la conexión ESPCAM por WebSocket o el despliegue en Heroku, no dudes en abrir un "issue" o enviar un "pull request".

## Créditos 🙌

Este proyecto fue creado por [PICAIO SAS] y está inspirado en proyectos similares de la comunidad de IoT y desarrollo web.

## Licencia 📝

Este proyecto está bajo la licencia [MIT](LICENSE).
