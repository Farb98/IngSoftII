# prueba tecnica microservicios spring boot

> Desarrollo del proyecto de software II
> Se desarrolla un microservicio en spring boot usuando buenas practicas de diseño y codificaion, 
> como los principios SOLID el enfoque ATDD y diferentes frameworks y librerias para optimizar el trabajo. 
> Asi como la implementación de comunicación asincrona

## Para usar este repositorio
Este proyecto contiene tanto el codigo fuente como un jar listo para su ejecucion, el codigo fuente 
es una aplicacion spring boot gestionada con maven, por lo cual podra clonarse como un proyecto o ejecutar la aplicacion usando el jar.
La aplicacion es autocontenida, cuando se inicia crea una base de datos H2 en memoria.

La aplicacion cuenta con una interface grafica para ver la documentacion de la API y probar los diferentes endpoints.

Se ha desarrollado un set de pruebas para validar las diferentes reglas de negocio, 
todas han sido probadas con exito, si alguna prueba falla la aplicacion no compila.

Todas las dependencias estan descritas en el fichero de configuracion de maven pom.xml

El puerto por defecto es el 8084 para evitar posibles conflictos

### Requisitos previos
java 8 o superior
navegador web
opcional 
git 
IDE de desarrollo

### Probar la aplicación mediante la interface web
1- Descargar como zip o bien clonar el repositorio usando git o cualquier asistente grafico
   Una vez descargado puede optar por ejecutar el jar y levantar la aplicacion o  recompilar el proyecto desde su IDE favorito
   
2- Descomprimir el paquete descargado.

3- Para ejecutar el jar use el siguiente comando sustituyendo $HOME por la ubicacion donde ha descargado el proyecto java -jar  $HOME/SWII_PROJECT__TEST/build/swwii_project-0.0.1-SNAPSHOT.jar

4- Verificar que ha inicado correctamente, si tinee problemas validar que el fichero .jar exista y rectificar la ruta 

5- Si ha decidido clonar el proyecto debera habrirlo en su IDE favorito.

# Prueba Unitarias
Se ha realizado un desarrollo basado en el enfoque ATDD, donde se han escrito todos los casos de prueba para validar las diferentes 
reglas de negocio y criterios de aceptacion. Dichas pruebas se lanzan de manera automática.

## Más informacion

Echo inquietudes comuniquese con Jorge Otálora, jorge.otalora@uptc.edu.co
