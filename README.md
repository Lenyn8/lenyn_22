# lenyn_22
-Abrir Play with Docker
-Ingresar el comando : docker run --name nginx -p 80:80 -d nginx 


-Para verificar si esta funcionando el servidor ponemos docker ps



Comandos Básicos de Docker 
docker run: Correr un contenedor
docker ps: Contenedores que están corriendo
(-- name serverweb): Colocar un nombre y sirve para identificar el docker y donde está corriendo
80:80: Maquina anfitriona
-d: Permite seguir ocupando la línea de comandos, si usamos el proceso pasa a segundo plano


-Creamos un documento en github (documento html)



-En la linea de comandos escribimos wget https://github.com/lenyn8/lenyn_22/blob/main/index2.html


-Para verificar si se cargo correctamente escribimos el comando ls

-Ingresamos el comando docker cp index2.html nginx:/usr/share/nginx/html/index2.html (se extrae o se añade la informacion del html que se creo en el repositorio) ---> (Presionamos Open Port y ponemos el puerto 80)

