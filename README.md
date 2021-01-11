# SfcDuino

Entorno gráfico para programar mediante grafcets (SFC) dispositivos Arduino y autómatas basados en los mismos, conforme a las 
normas UNE-EN 60848 y UNE-EN 61131-3. Esta herramienta ha sido creada y diseñada desde cero en C# y C++ sin utilizar librerías de terceros.

El software permite diseñar gráficamente uno o varios GRAFCETs para posteriormente compilarse y enviarse al dispositivo.
Permite el uso de varibles auxiliares, tales como:
- BOOL: marca boleana.
- INT: para realizar operaciones matemáticas (suma, resta, multiplicación y división) o a modo de contadores.
- TP: temporizador de único pulso.
- TON: temporizador con retardo a la conexión.
- TOF: temporizador con retardo a la desconexión.

![CapturaSfcDuino](https://user-images.githubusercontent.com/77203519/104228022-8de76f80-544a-11eb-8ac8-9ac5b36944bb.png)

Dispositivos soportados hasta ahora:

- Arduino UNO (R3)
- Arduino Leonardo
- ArdBox Analog

Queda prohibida la venta, reproducción, alteración y/o transformación de este software (ejecutables, código fuente, librerías y todos los ficheros relacionados con SfcDuino y Sfclib). Este software es gratuito y queda limitado a usos sin fines lucrativos.
Si desea colaborar en el desarrollo de este software u obtener el código fuente del mismo (con licencia GPL3) contacte con el autor.
