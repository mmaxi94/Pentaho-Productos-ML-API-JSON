# Pentaho-Productos-ML-API-JSON

## Objetivo:
Realizar la busqueda de 3 productos de Mercadolibre Argentina utilizando las API's publicas de ML y generando un archivo JSON de salida por cada una.

## Funcionamiento del proceso:
El proceso se divide en 3 etapas.
- 1° etapa: Busqueda de cada uno de los productos utilizando diversas API's con el fin de obtener los atributos que sean de interes para cada producto.
- 2° etapa: Formateo final del archivo JSON
- 3° etapa: eliminacion de archivos JSON intermedios y/o vacios debido a errores de parametros ingresados por el usuario

## ¿Como ejecutarlo?:
Descomprimir el .rar en el directorio deseado de su computadora, y ejecutar el job "main.kjb". Las instrucciones para el ingreso de los parametros se encuentran en las notas del job.

## Consideraciones:
- La estructura del JSON final generado se puede validar en sitios web como, por ejemplo, https://jsonformatter.curiousconcept.com/#
