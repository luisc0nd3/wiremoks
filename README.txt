--curl example
curl http://localhost:8080/get/this

--arrancar el jar
java -jar D:\2022\wiremoks\wiremock-jre8-standalone-2.32.0.jar --verbose --port 9999 --global-response-templating

--url
http://localhost:9999/api/mytest

--curl 
curl http://localhost:8080/api/mytest


--mappings:
    contiene ficheros en formato JSON con las combinaciones de request a las que atienda y las responses que tiene que dar.

--_files: 
    contiene los ficheros con el contenido de las responses, y que son referenciados desde los mappings. 
    Es posible no usar un fichero y especificar la respuesta en la configuración pero es algo que, 
    a poco que crezca la respuesta, no te recomiendo.
