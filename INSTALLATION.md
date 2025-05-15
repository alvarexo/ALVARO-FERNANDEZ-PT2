# INSTALACIÓN OWNCLOUD ISARDVDI

![imatge](https://github.com/user-attachments/assets/c722cb22-5ab8-44a0-9c15-5d3ee549be46)

![imatge](https://github.com/user-attachments/assets/63b6b725-148a-42e6-9be4-54bc7a8ce448)

![imatge](https://github.com/user-attachments/assets/2e5a612a-8b62-4f39-b8c1-5b1c6d0ea765)

Con esto, ya tendriamos creado nuestro escritorio nuevo para empezar a hacer la practica de instalación.

![imatge](https://github.com/user-attachments/assets/886500d2-1467-4cae-b16c-17740e458318)

Ahora vamos a editar nuestro escritorio correctamente.

![imatge](https://github.com/user-attachments/assets/a78c1f23-11be-47cb-9afc-7e55961a492e)

Esta sería la configuración correcta que le asignamos al escritorio UBUNTU, y ahora si que si, ya podemos empezar a hacer la instalación de OWNcloud.

![imatge](https://github.com/user-attachments/assets/e0764638-b25f-4f79-94df-8abb87c609e1)

Configuración correctamente configurada, ya esta listo para enviarlo.

## Actualizamos la máquina

![imatge](https://github.com/user-attachments/assets/470ba6ff-4937-4069-af19-ca6d3d8fbd77)

![imatge](https://github.com/user-attachments/assets/474f333d-a45a-493b-b375-801dd5afce28)

Una vez ya hemos actualizado la máquina correctamente sin ningún error, ya podemos pasar al siguiente paso, que sería instalar APACHE.

![imatge](https://github.com/user-attachments/assets/938b297b-876e-420a-8fdb-206b510513e4)

Este es el comando que tendremos que utilizar para proceder a la instalación de apache.

Ahora, después de instalar apache, vamos a proceder a la instalación del servidor de base de datos mysql.

![imatge](https://github.com/user-attachments/assets/ae2646c1-8127-4f82-b371-201cd84fe000)

Ya tendríamos instalado la base de datos y podríamos pasar a instalar las librerias PHP que tienen utilidad las aplicaciones.

Procedemos a instalar las librerias PHP para las aplicaciones.

![imatge](https://github.com/user-attachments/assets/06d71713-1941-4c7e-be3d-12255d7415e4)

![imatge](https://github.com/user-attachments/assets/2e403382-f612-4069-8d98-c4da5ac71179)

Ya estaría, este es el comando que tenemos que utilizar para instalar las librerias PHP.

Y ahora por ultimo de instalaciones, reiniciaremos el servidor de apache con el siguiente comando:

![imatge](https://github.com/user-attachments/assets/0bb7487e-2505-43ee-a009-e908be9bf6c5)

Con esto ya reiniciaríamos el servidor.

## Configuración de base de datos

Lo primero que haremos para configurar la base de datos, será acceder a la propia consola de ella.

![imatge](https://github.com/user-attachments/assets/236c8786-e101-45f4-b54b-3abda9580340)

ahora ya estamos dentro de nuestra consola y lo que haremos a continuación es crear la base de datos en el mysql.

![imatge](https://github.com/user-attachments/assets/de24b1d9-2f39-4b6e-87a6-e2239f7fa3bd)

Ahora crearemos nuestro usuario que tendra su propia contrseña y su nombre de usuario para la base de datos, que es lo que sale indicado en azul.

![imatge](https://github.com/user-attachments/assets/aac2bf23-b1ec-440e-b2ca-858bf89da891)

Por último dentro de la base de datos, lo que hacemos es darle permisos/privilegios al usuario.

![imatge](https://github.com/user-attachments/assets/f10a0ddd-3825-4068-83f8-cceafb08bce2)

Y para finalizar la configuración de la base de datos, salimos simplemente haciendo lo siguiente:

![imatge](https://github.com/user-attachments/assets/99ec2af3-7ac5-4791-ab9a-55dde1dcc81e)

ahora lo que vamos a hacer será probar la conexión a la base de datos.

![imatge](https://github.com/user-attachments/assets/719475c1-cf07-4da1-a3fe-5bf844a2c310)

![imatge](https://github.com/user-attachments/assets/2b262337-b7a6-461e-afda-55f1e9716cf8)



### Descargamos archivo .zip del servidor Owncloud

https://download.owncloud.com/server/stable/owncloud-complete-20240724.zip


![imatge](https://github.com/user-attachments/assets/d13fa750-23ec-45ba-990a-bd4cdb8b4cf1)

Cuando ya hemos instalado el archivo vamos a tener que hacer lo siguiente:

Ahora entramos al directorio de la siguiente manera

![imatge](https://github.com/user-attachments/assets/3bbdd08e-7ad0-497d-855c-3648102ac537)

Modifica el nombre del archivo como quieras, en este caso yo le he llamado appweb.zip

![imatge](https://github.com/user-attachments/assets/0f87ed92-ddfb-4e2a-9ac4-f45df820b12b)

Ahora vamos a descomprimir el archivo que hemos descrgado "appweb"

![imatge](https://github.com/user-attachments/assets/bf64542e-fc2c-4421-aa44-186119733e39)

Copiamos los archivos a la carpeta /var/www/html y modificamos el nombre del archivo por el que hemos puesto, y lo descomprimimos 

![imatge](https://github.com/user-attachments/assets/c5a96476-6c56-40a8-b2ec-031a1cd29615)

Ahora eliminamos la carpeta que hemos creado cuanod hemos descomprimido el archivo

![imatge](https://github.com/user-attachments/assets/1f2e2de8-6f5d-46a3-96de-27a80cda7eef)

por último eliminamos el archivo index.html del servidor de apache.

![imatge](https://github.com/user-attachments/assets/d84b89c9-6511-4f7e-b11c-1c537c00d012)

Ahora vamos a proceder a añadir permisos.

Estos son todos los permisos que vamos a añadir.

![imatge](https://github.com/user-attachments/assets/a2d47143-4413-4dc3-a958-b434c4cc0fe0)

Por último, vamos a ir al navegador para ver que todo funcione correctamente

http://localhost entramos en este link y entramos con nuestros datos 

usuari: usuario
contrasenya: password
base de dades: bbdd

Cuando entramos al link, tendremos que instalar versiones mas nuevas de librerias PHP, asi que vamos a hacerlo.

![imatge](https://github.com/user-attachments/assets/8aeabd4a-1886-4f0a-afb0-4f96ef2014a1)

Primero instalaremos los requisitos previos del PPA

![imatge](https://github.com/user-attachments/assets/79a4582a-45de-4082-aaa8-1da265aa9082)

Seguidamente instalaremos todas las herramientas que nos hagan falta para la instalación

![imatge](https://github.com/user-attachments/assets/4d3d6c23-14d4-4e9a-bdab-97328adb4943)

Ahora actualizamos los repos del sistema para acabar

![imatge](https://github.com/user-attachments/assets/c22c9fdf-eadd-487b-90f5-565587ba63a6)

Y ahora ya empezamosa a instalar las nuevas librerias PHP mas nuevas, para que podamos entrar en owncloud.

![imatge](https://github.com/user-attachments/assets/c55b8c61-2d08-4026-8168-f307ae80b227)

![imatge](https://github.com/user-attachments/assets/2e180def-3aa8-4050-915c-4c3ca7700a86)

![image](https://github.com/user-attachments/assets/13f546cb-2a6d-4a95-8c7b-2c6881502061)

El siguiente paso y muy importante, es que vamos a elegir la version PHP, para que sea compatible y nos deje entrar a Owncloud.

![image](https://github.com/user-attachments/assets/7a294e57-171a-4d31-9f94-526d7d5b0222)

Y ahora tocara elegir

![image](https://github.com/user-attachments/assets/a7e9d56f-7895-45d9-a134-ac24d61c0565)

Como pone en la imagen , elegiremos la segunda opción.

Y ahora si que si, para finalizar la instalación, tendremos que activar los modulos del servidor apache, y reiniciarlo, y lo haremos de la siguiente manera:

![image](https://github.com/user-attachments/assets/ddb9e118-c51f-4978-b090-84124d100db1)

Y por ultimo reiniciamos APACHE.

![image](https://github.com/user-attachments/assets/0007c503-6978-4eaf-b196-b4e0def64f34)

Ahora volvemos a probar a entrar en el http://localhost en el navegador, para poder empezar la configuración.

![image](https://github.com/user-attachments/assets/0134898b-f9bb-46a2-a3e7-28c99b6e703e)

![image](https://github.com/user-attachments/assets/0cfdce44-19d3-4fb8-8f74-e6daf40e9fb4)


