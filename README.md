# JMeterBase


Pasos a seguir en la instalación y configuración de JMeter. 

Descargar JDK Java 23 o anterior reciente. 
https://download.oracle.com/java/23/latest/jdk-23_windows-x64_bin.exe (sha256)

Descargar la versión en .zip (Binaries) de:
apache-jmeter-5.6.3 Apache JMeter - Download Apache JMeter

En la unidad C:\
Crear la carpeta "Programas"

En la carpeta "Programas" Descomprimir: apache-jmeter-5.6.3.zip
C:\Programas\apache-jmeter-5.6.3

Configurar las siguientes Variables del sistema: 
JAVA_HOME
CLASSPATH
JMETER_HOME
JMETER_OPTS
JVM_ARGS
HEAP


JAVA_HOME
C:\Program Files\Java\jdk-22

CLASSPATH
C:\Programas\apache-jmeter-5.6.3\lib

JMETER_HOME
C:\Programas\apache-jmeter-5.6.3

JMETER_OPTS
"-Xmx2048m -XX:+UseG1GC -Dproperty=value"

JVM_ARGS
-Xms2048m -Xmx2048m

HEAP
-Xms2g -Xmx2g -XX:MaxMetaspaceSize=512m

Editar PATH ---> 
%JMETER_HOME%\bin
%JAVA_HOME%\bin


Guardar el Script en: C:\Programas\apache-jmeter-5.6.3\bin\scripts\Test_Plan.jmx
Configurar los Hilos de la ejecución
Run del Script: 



