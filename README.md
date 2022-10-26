# lenyn_22
-Abrir Play with Docker
-Ingresar el comando : docker run --name nginx -p 80:80 -d nginx 

[![imagen-2022-10-26-152054448.png](https://i.postimg.cc/prdV2H1y/imagen-2022-10-26-152054448.png)](https://postimg.cc/N9Wv4Wtw)


-Para verificar si esta funcionando el servidor ponemos docker ps

[![imagen-2022-10-26-161832353.png](https://i.postimg.cc/3w6hpc1b/imagen-2022-10-26-161832353.png)](https://postimg.cc/GBk6nzZk)

Comandos Básicos de Docker 
docker run: Correr un contenedor
docker ps: Contenedores que están corriendo
(-- name serverweb): Colocar un nombre y sirve para identificar el docker y donde está corriendo
80:80: Maquina anfitriona
-d: Permite seguir ocupando la línea de comandos, si usamos el proceso pasa a segundo plano


-Creamos un documento en github (documento html)

[![imagen-2022-10-26-161944426.png](https://i.postimg.cc/bJXMqc38/imagen-2022-10-26-161944426.png)](https://postimg.cc/v1zXvKJS)


-En la linea de comandos escribimos wget https://github.com/lenyn8/lenyn_22/blob/main/index2.html

[![imagen-2022-10-26-162019097.png](https://i.postimg.cc/sDfLjJ9B/imagen-2022-10-26-162019097.png)](https://postimg.cc/Rq8dGKY9)


-Para verificar si se cargo correctamente escribimos el comando ls

[![imagen-2022-10-26-162019097.png](https://i.postimg.cc/sDfLjJ9B/imagen-2022-10-26-162019097.png)](https://postimg.cc/Rq8dGKY9)

-Ingresamos el comando docker cp index2.html nginx:/usr/share/nginx/html/index2.html (se extrae o se añade la informacion del html que se creo en el repositorio) ---> (Presionamos Open Port y ponemos el puerto 80)

