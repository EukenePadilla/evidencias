# TAREA 4: Virtual Hosts

Primero vamos a crear una copia de 00-default.conf. 

![](img/tarea4_1.png)

Entramos en el archivo (utilizando nano) y vamos a indicarle la URL que tenemos que poner en el navegador(ServerName) y donde están situados los archivos de nuestra carpeta de cliente.
En nuestro caso están en /var/www/cliente.

![](img/tarea4_2.png)

A continuación, habilitaremos la URL mediante el comando "sudo a2ensite cliente.conf".

![](img/tarea4_3.png)

Con servidor seguiremos los mismos pasos que con cliente.

![](img/tarea4_4.png)

![](img/tarea4_5.png)

Para terminar reiniciaremos el servidor usando los siguientes comandos:

![](img/tarea4_6.png)

Y poniendo en nuestro navegador las direcciones nos saldrá lo escrito en el index.html de cada carpeta (cliente y servidor).
![](img/tarea4_7.png)