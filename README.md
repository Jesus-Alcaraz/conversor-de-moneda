<h1 align="center"> Challenge Conversor De Monedas - Alura/Oracle One </h1>

<p align="center"><img src="https://github.com/Micky169/conversor-de-moneda/assets/139664430/7107852a-ba3d-4941-ba1d-c376d8bbd30e"></p>

![Maven Central Version](https://img.shields.io/maven-central/v/org.junit.jupiter/junit-jupiter-api?versionPrefix=5.10.2&style=for-the-badge&logo=junit5&label=JUnit5&color=824D74link=https%3A%2F%2Fjunit.org%2Fjunit5%2Fdocs%2Fsnapshot%2Frelease-notes%2F)
![Static Badge](https://img.shields.io/badge/Java-17.0.9-blue?style=for-the-badge&link=https%3A%2F%2Fwww.oracle.com%2Fjava%2Ftechnologies%2Fjavase%2Fjdk17-archive-downloads.html)
![Static Badge](https://img.shields.io/badge/Json-violet?style=for-the-badge&logo=Json&logoColor=grey&labelColor=black)
![Maven Central Version](https://img.shields.io/maven-central/v/com.google.code.gson/gson?versionPrefix=2.10.1&style=for-the-badge&label=Gson&color=153448&link=https%3A%2F%2Fgithub.com%2Fgoogle%2Fgson)
![Static Badge](https://img.shields.io/badge/Release%20Date-April-5F374B?style=for-the-badge&labelColor=416D19)
![Static Badge](https://img.shields.io/badge/status-finished-yellow?style=for-the-badge&labelColor=76885B)
<p align="center"><img src="https://img.shields.io/badge/Licence-Mit-fedcba?style=for-the-badge&labelColor=black"></p>


## Índice

[Descripción del proyecto](#descripción-del-proyecto)

[Estado del proyecto](#Estado-del-proyecto)

[Funcionalidades de la aplicación](#Funcionalidades-de-la-aplicación)

[Acceso al proyecto y tecnologías utilizadas](#Acceso-al-proyecto-y-tecnologías-utilizadas)

[Consideraciones](#consideraciones)



## Descripción del proyecto

Challenge de Alura/Oracle Next Education, que consistio en el desarrolló de una aplicacion que realiza conversiones de devisas por medio de solitudes a una API.
El usuario final puede consultar, filtrar las divisas de su interes y generar su conversión.


## Estado del proyecto

Completado.



## Funcionalidades de la aplicación 

* Muestra las opciones para la conversión de las divisas
* Muestra las divisas disponibles a convertir 
* Muestra el tipo de cambio de la divisa 
* Realizar conversiones entre divisas  
* De manera automatica guarda la api key
* En el menú da la opcion para generar una nueva conversión.


## Acceso al proyecto y tecnologías utilizadas

Pasos para la instalacion
   1. Obtener su API key
   2. Descargar el JRE de java para poder ejecutarlo
   3. Clone el proyecto o descárguelo
   4. Ejecutar el archivo jar que hay dentro

### 1. Obtener la API key
El conversor de monedas utiliza una API-KEY para funcionar por lo que debe registarse en [ExchangeRateApi](https://v6.exchangerate-api.com) para obtener la respectiva API-KEY
### 2. Descargar el JRE
Para poder correr la application es necesario tener el entorno de ejecucion pertinente puede [descargarlo](https://www.oracle.com/java/technologies/downloads/)
### 3. Descargar el proyecto
Descargar el proyecto desde el link del repositorio y descomprima archivo zip.
Crea un nuevo proyecto Java.
Crea un archivo apiKey en la raíz del proyecto y guardar la apiKey en el archivo apiKey.txt. Ver enlace para apikey: https://v6.exchangerate-api.com.  
Descarga gson-2.10.1.jar y agregalo a la ruta del paquete.
Haz click en el Run o presiona Crtl+Shift+F10 en la clase Principal.
### 4. Ejecute el archivo jar dentro del proyecto
 - Pulse Windows + R y escriba cmd, si tiene otro sistema abra la línea de comandos
 - Ejecute el siguiente comando `java -jar (rutaAbsoluta del archivo jar)`
 - Debera ingresar su API key ya que la aplicacion se la pedira.

gson-2.10.1
Ver enlace: https://mvnrepository.com/artifact/com.google.code.gson/gson

API-KEY del sitio: https://v6.exchangerate-api.com

Versiones probadas desde consola e Intellij: openjdk-17 ; openjdk-21
(Verificar que las versiones de 'javac' y 'java' (compilador y jre) coincidan en caso de tener dos o más versiones de java instaladas si se desea compilar desde la consola)

## Consideraciones

Para poder ejecutar la aplicacion es necesario el JRE 17.0.9 o una version superior.

## Nota:

El archivo apiKey.txt deberá crearse o moverse dentro de la carpeta classes después de la compilación, dentro deberá contener la clave de la api del usuario y puedan realizarse las consultas. Puede optar por asignarla directamente dentro del código y eliminando la funcionalidad de lectura de archivo.

## Para probar en Itellij



## Contacto
 * [Linkedin](https://www.linkedin.com/in/jesus-alcaraz-)
 


