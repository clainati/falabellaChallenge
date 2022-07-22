# Performance Falabella Challenge

## Como usar

Para la utilizacion de la primera parte de la prueba (prueba a servicios) se creo un postman_collection.json con los casos funcionales y a su vez la parte automatizada de estos.
En el caso de la prueba de performance se adjunto el proyecto de jmeter 5.5 para que solo deban clonar y ejecutar los comandos que listare.
```
$ Ejecucion a traves de interfaz grafica(usa mas recursos del equipo) bastara con abrir el ApacheJmeter.jar de la carpeta jmeter5.5 
$ Ejecucion a traves de CLI (se recomienda utilizar esta) en la carpeta bin de jmeter se debe ejecutar el siguiente comando jmeter -n –t falabellaChallenge.jmx -l resultadosPrueba.jtl
$ Ejecucion y generacion de reporte html, a traves de la CLI en la carpeta bin de jmeter se debe ejecutar el siguiente comando jmeter -n -t falabellaChallenge.jmx -l resultadosPrueba.jtl -e -o C:\xx\xx\xx\apache-jmeter-5.5\bin\carpetaQueSeutilizaraParaDejarLosresultados(debe estar vacia)
```

## Como obtener reporte html

Para sacar el reporte html que nos entrega jmeter existen 2 maneras
```
$ Ejecutar jmeter con interfaz grafica e ir a la opcion tools "generate html report", se debe colocar la ruta del jtl en el primer campo luego la del user.properties y una carpeta de salida que este vacia 
$ Ejecucion a traves de CLI en la carpeta de raiz de jmeter se debe ejecutar el siguiente comando jmeter -g  C:\xx\xx\Documents\apache-jmeter-5.5\bin\nombredeResultados.jtl -e -o pathDondeQuierenDejarElhtml(debe estar vacia)
```

### Pre-requistos

Se necesitan los siguientes pre requisitos

* java 1.8 o superior
* Postman

