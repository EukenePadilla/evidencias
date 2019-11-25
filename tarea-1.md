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

