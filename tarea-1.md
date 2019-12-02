# INSTALAR UBUNTU EN UN SERVIDOR Y CONECTARNOS VIA SSH

Podemos comprobar con la siguiente imagen que el servidor esta encendido y que funciona correctamente.
![](img/tarea1_2.png)

Para conectarnos a la máquina virtual creada anteriormente, tendremos que ir a Actions->Connect.

![](img/tarea1_3.png)

Con la clave creada anteriormente, cuando creamos la máquina virtual, deberemos darle los permisos necesarios y después nos podremos conectar copiando la línea de comando que nos ponen como ejemplo.

![](img/tarea1_4.png)

Lo haremos desde la carpeta donde está la key guardada.

![](img/tarea1_1.png)

# HABILITAR SSH E INSTALAR APACHE2 

Actualizamos el servidor.

![](img/tarea1_5.png)

Instalamos los servicios de ssh.

![](img/tarea1_6.png)

Reiniciamos los servicios de ssh.

![](img/tarea1_7.png)

Volvemos a actualizar.

![](img/tarea1_8.png)

E instalamos el apache2.

![](img/tarea1_9.png)

Creamos un archivo igual que 000-default.conf y le cambiamos el nombre por eukene.io.conf.

![](img/tarea1_10.png)

Entramos en el archivo que acabamos de crear.

![](img/tarea1_11.png)

Ahora añadiremos un par de lineas para indicar a ruta.

![](img/tarea1_12.png)

Y reiniciamos el servicio de apache2.

![](img/tarea1_13.png)

# MYSQL Y PHP 

Instalamos el servidor de mysql.

![](img/tarea1_14.png)

Aquí definimos la constraseña y otras cosas de seguridad de mysql.

![](img/tarea1_15.png)
![](img/tarea1_16.png)

Vamos a instalar php en la máquina virtual.

![](img/tarea1_17.png)

Le decimos que usaremos apache2 para ejecutar phpMyAdmin.

![](img/tarea1_18.png)

Le diremos que si para poder configurar manualmente la administración de la base de datos.

![](img/tarea1_19.png)

Pondremos una contraseña, en nuestro caso será 1234.

![](img/tarea1_20.png)

Elegimos Unix Socket, ya que esto proporciona el mejor rendimiento.

![](img/tarea1_21.png)

Llamaremos a la base de datos phpmyadmin.

![](img/tarea1_22.png)

Por último le diremos que el usuario con el que se va a conectar sera con root.

![](img/tarea1_23.png)
