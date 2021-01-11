# SfcDuino

Entorno gráfico para programar mediante grafcets (SFC) dispositivos Arduino y autómatas basados en los mismos, conforme a las 
normas UNE-EN 60848 y UNE-EN 61131-3. Esta herramienta ha sido creada y diseñada desde cero en C# y C++ sin utilizar librerías de terceros.

El software permite diseñar gráficamente uno o varios GRAFCETs para posteriormente compilarse y enviarse al dispositivo.

Permite el uso de varibles auxiliares, tales como:
- BOOL: marca boleana.
- INT: para realizar operaciones aritméticas (suma, resta, multiplicación y división) o a modo de contadores.
- TP: temporizador de único pulso.
- TON: temporizador con retardo a la conexión.
- TOF: temporizador con retardo a la desconexión.

![CapturaSfcDuino4](https://user-images.githubusercontent.com/77203519/104244042-eece7200-5461-11eb-8aa0-7b68c59e6f18.png)

Dispositivos soportados hasta ahora:
- Arduino UNO (R3)
- Arduino Leonardo
- ArdBox Analog

Para su uso se requiere la instalación previa del IDE oficial de Arduino (versión 1.8.6 en adelante):
- IDE oficial Arduino: https://www.arduino.cc/en/software
- .NET Framework 4.6.1: https://www.microsoft.com/es-es/download/details.aspx?id=49982

Queda prohibida la venta, reproducción, alteración y/o transformación de este software (ejecutables, código fuente, librerías y todos los ficheros relacionados con SfcDuino y SfcLib) si no se dispone de autorización expresa por parte del autor (con licencia GPL3).
Este software es gratuito y queda limitado a usos sin fines lucrativos.
Si desea colaborar en el desarrollo de este software u obtener el código fuente del mismo (con licencia GPL3) contacte con el autor.

Pre-release V1.0:
- Descarga: https://github.com/RLJuan/SfcDuino-Builds/releases/download/SfcDuinoV1.0/SfcDuino1.0.zip
