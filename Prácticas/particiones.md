**Partición**

Una partición és un contenedor donde le ponemos una etiqueta.

![alt text](http://2.bp.blogspot.com/-QIbi2hhPrB4/VA8cjzW_EII/AAAAAAAACdE/x9dmnkIaJTw/s1600/GParted%2Bsda.png)

**Sistema de Archivos**

Para que funcione la partición tenemos que crear dentro de nuestra partición un **sistema de archivos**, lo que hace és que crea estanterías dentro de nuestro contenedor (partición), y para hacerlo lo haremos con **mkfs."nombre del archivo".

![alt text](https://i1.wp.com/recursostic.educacion.es/observatorio/web/images/upload/ccam0040/sistemaficheroslinux/sistema_archivos_linux_html_49229bb2.jpg)

Tenemos diferentes sistema de archivos como:

**FAT 32** **F**ILE **A**LLOCATION **T**ABLE que són de **32 bits**

**NTFS** és como un **FAT32** pero de **64 bits** tiene muchas más seguridad de archivos y permisos. 

Después de haber terminado de hacer las particiones tendremos que utilizar el **partprobe** és un comando para leer el disco duro y que nos reconozca las particiones, si no tendremos que reiniciar el ordenador y perderemos tiempo.

Con el **partprobe** és el método que tenemos que utilizar siempre y que será útil.

Pero tenemos un **apaño** que si por una razón u otra no nos va el **partprobe** tenemos el:

**Kpartx -a "disco"**

Y nos quedará guardado en **mapper** y para entrar deberemos de hacer **ls "disco"/mapper/"disco". 

**Comandos Particiones** 

**a** -> partición boot

**n** -> creamos partición

**l** -> partición lógica

**p** -> partición primaria 

**e** -> partición extendida

**t** -> cambiamos tipo 

**82** -> swap

**7** -> ntfs 




