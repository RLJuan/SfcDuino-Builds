# SfcDuino

Entorno gráfico para programar mediante grafcets (SFC) dispositivos Arduino y autómatas basados en los mismos.
Esta herramienta ha sido creada y diseñada desde cero en C# y C++ sin utilizar librerías de terceros.

El software permite diseñar gráficamente uno o varios GRAFCETs para posteriormente compilarse y enviarse al dispositivo.

## Variables de entorno
Permite el uso de varibles tales como:
- BOOL: marca booleana.
- INT: para realizar operaciones aritméticas (suma, resta, multiplicación y división) o a modo de contadores.
- TP: temporizador de único pulso.
- TON: temporizador con retardo a la conexión.
- TOF: temporizador con retardo a la desconexión.

![CapturaSfcDuino4](https://user-images.githubusercontent.com/77203519/104244042-eece7200-5461-11eb-8aa0-7b68c59e6f18.png)

## Dispositivos
Dispositivos soportados hasta ahora:
- Arduino UNO (R3)
- Arduino Leonardo
- ArdBox Analog
- **NUEVO (v1.0b - 08/02/2021)**: Arduino MEGA 2560 (R3)

Próximamente (febrero 2021):
- Arduino NANO

## Últimos cambios
Cambios realizados desde la última versión:
- **v1.0c (09/02/2021):** Ahora puede leerse el "Name" (descripción del puerto) de dispositivos Arduino con conversores USBSerial baratos (por ejemplo CH340G, muy utilizado en réplicas chinas).

## Requisitos
Para su uso se requiere la instalación previa del IDE oficial de Arduino (versión 1.8.6 en adelante):
- [IDE oficial de Arduino](https://www.arduino.cc/en/software)
- [.NET Framework 4.6.1](https://www.microsoft.com/es-es/download/details.aspx?id=49982)

## Licencia
_Queda prohibida la venta, alteración y/o transformación de este software (ejecutables, código fuente, librerías y todos los ficheros relacionados con SfcDuino y SfcLib) si no se dispone de autorización expresa por parte del autor (con licencia GPL3).
Este software es gratuito y queda limitado a usos sin fines lucrativos._
Si desea colaborar en el desarrollo de este software u obtener el código fuente del mismo (con licencia GPL3) contacte con el autor ([@RLJuan](https://github.com/RLJuan)).

### **[Descarga SfcDuino Pre-release v1.0c](https://github.com/RLJuan/SfcDuino-Builds/releases/download/v1.0c/SfcDuino1.0c.zip)**
