# XSSWebServer

Par de Web Servers en Java uno de ellos vulnerable a XSS y el otro representa el Web Server del Atacante.

Encontrara 4 archivos:

+ Web Server vulnerable a XSS
  - WebServerXss.zip que es un proyecto Java creado en Eclipse IDE for Java Developers Version: 2024-12 (4.34.0)
  - WebServerXss.jar que es el JAR ejecutable para correr sobre JRE build 21+35-2513
 
+ Web Server del Atacante
  - WebServerAtacante.zip que es un proyecto Java creado en Eclipse IDE for Java Developers Version: 2024-12 (4.34.0)
  - WebServerAtacante.jar  que es el JAR ejecutable para correr sobre JRE build 21+35-2513

*Si no cuenta con eclipse no importa, puede usar cualquier otro IDE de su preferencia y crear un nuevo proyecto para cada uno
de los Web Servers ya que solo constan de una clase.

+ Forma de ejecucion

Una vez que ya cuenta con la maquina virtual configurada en computadora personal, ya puede proceder a ejecutar los webservers.
Abra una ventana de consola para poder ejecutar cada uno de los Web Servers, trasladese al directorio donde haya colocado los 
archivos JAR y allí podrá ejecutar los comandos siguientes:

    - Web Server vulnerable
        java -jar WebServerXss.jar
        
    - Web Server Atacante
        java -jar WebServerAtacante.jar 
