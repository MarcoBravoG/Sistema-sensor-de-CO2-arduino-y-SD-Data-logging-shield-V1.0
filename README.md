# Sistema-sensor-de-CO2-arduino-y-SD-Data-logging-shield-V1.0

El siguiente progrma desarrolloda se han cargado las siguientes librerias:
Liberia Sensor de CO2
Libreria del adaptador de micro sd Data Logging Shield v1.0
seguidamente se puede observar el codigo desarrollado
y finalmente el circuito del proyecto


Lectura de txt a .csv en excel
https://www.youtube.com/watch?v=meF1XotsY9o&t=48s&ab_channel=J%26CWorldTricks



Como ejecutar el programa
Libreria del adaptador de micro sd Data Logging Shield v1.0
1- se necesita ejecutar el  programa Arduino_RTC_Setup en el arduino con el shield sd Data Logging Shield V1.0   esto permite establecer la hora
2. Finalemnte ejecutar el programa programaCo2MicroSD en este programa permite correr nuestro programa para recolectar los datos sensados y almacenar en la sd

Los pasos previos son: caragr librerias  como:
-CO2Sensor-master
-RTClib-masteer

link de videos para reforzar 

-https://www.youtube.com/watch?v=TKY-ITT_PG4&ab_channel=MYBOTIC
-https://www.youtube.com/watch?v=uZCsFyeCwB8&ab_channel=AEQ-WEB

si precesntamos un error de este tipo 
ResolveLibrary(Adafruit_I2CDevice.h)C:\Users\ZAKARIYA\Documents\Arduino\libraries\RTClib-2.0.3\src/RTClib.h:25:10: fatal error: Adafruit_I2CDevice.h: No such file or directory

It seems your RTClib is expcting Adfruit library. Try Arduino IDE--> Tools --> Library manager and "install"latest version of Adafruit BusIO and rebuild

solucionamos con la libreria  Adafut_BusIO





