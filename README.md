# SfcDuino
Entorno gráfico para programar mediante grafcets (SFC) dispositivos Arduino y autómatas basados en los mismos, cumpliendo normas UNE-EN 60848 y UNE-EN 61131-3.

Esta herramienta ha sido creada y diseñada desde cero en C# y C++ sin utilizar librerías de terceros.

El software permite diseñar gráficamente GRAFCETs, para posteriormente compilar y enviar al dispositivo. El trazado automático realiza las conexiones entre los elementos ahorrando tiempo, además de evitar errores de diseño por parte del usuario, ya que, el algoritmo se centra en cumplir cada una de las reglas elementales impuestas en las normas UNE-EN mencionadas anteriormente.

![CapturaSfcDuino4](https://user-images.githubusercontent.com/77203519/104244042-eece7200-5461-11eb-8aa0-7b68c59e6f18.png)

## Variables soportadas ⛓
Además de implementar gráficamente _etapas_, _acciones_ y _transiciones_ para la creación de GRAFCETs, el entorno soporta los siguientes tipos de variables:
- _BOOL_: marca booleana.
- _INT_: para realizar operaciones aritméticas (suma, resta, multiplicación y división) o a modo de contadores.
- _TP_: temporizador de único pulso.
- _TON_: temporizador con retardo a la conexión.
- _TOF_: temporizador con retardo a la desconexión.

## Dispositivos 🔌
Dispositivos soportados hasta ahora:
- Arduino UNO (R3)
- Arduino Leonardo
- ArdBox Analog (Industrial Shields)
- **NUEVO (v1.0b - 08/02/2021)**: Arduino MEGA 2560 (R3)

Próximamente:
- Arduino NANO

## Últimos cambios 🛠
Cambios realizados desde la última versión:
- **v1.0c (09/02/2021):** ahora puede leerse la variable _name_ (descripción del puerto) de dispositivos Arduino con conversores USB/Serial baratos (por ejemplo _CH340G_, muy utilizado en réplicas chinas).

## Requisitos ✒️
Para su uso se requiere la instalación previa del IDE oficial de Arduino (versión 1.8.6 en adelante):
- [IDE oficial de Arduino](https://www.arduino.cc/en/software)
- [.NET Framework 4.6.1](https://www.microsoft.com/es-es/download/details.aspx?id=49982)

## Licencia 🧾
_Queda prohibida la venta, alteración y/o transformación de este software (ejecutables, código fuente, librerías y todos los ficheros relacionados con SfcDuino y SfcLib) si no se dispone de autorización expresa por parte del autor (con licencia GPL3).
Este software es gratuito y queda limitado a usos sin fines lucrativos._

Si desea colaborar en el desarrollo de este software u obtener el código fuente del mismo (con licencia GPL3) contacte con el autor ([@RLJuan](https://github.com/RLJuan)).

## Descarga ⚡️
### **[Descarga SfcDuino Pre-release v1.0c](https://github.com/RLJuan/SfcDuino-Builds/releases/download/v1.0c/SfcDuino1.0c.zip)**
