# esp-ia
Sistema de identificación de personas con o sin barbijo

## IDE
Sobre el entorno de desarrollo


Se sugiere utilizar el IDE Visual Studio Code por su detección de errores mientras se escribe el código, función de autocompletado, guías de identado, accesos directo al código de librerías incluídas, etc. 
Es fundamental instalar las extensiones “Arduino for Visual Studio Code” y “C/C++ Intellisense”
-https://www.luisllamas.es/arduino-visual-studio-code/
Para instalar la placa ESP32 en Arduino IDE
-https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/

## Proyecto de prueba


Luego de probar el “Hello World” que en el caso de un microcontrolador sería el “Blink LED”, puede intentar usar el ejemplo para ESP32-CAM donde podrá visualizarse desde un browser (a través de una IP) el streaming de la cámara incorporada.
En el código es importante definir la cámara que usará el módulo, por lo tanto hay que descomentar la línea 
#define CAMERA_MODEL_AI_THINKER // Has PSRAM

Habilitar la cámara que posee el módulo y escribir las credenciales de acceso a la red Wifi (código resaltado )

