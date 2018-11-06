Si queremos cambiar la **password de root** y por alguna casualidad no la sabemos o el que antes trabajaba no nos la dijo, lo que debemos de hacer es:

- Abrimos la terminal.

- Y ponemos # **sudo passwd root** y nos pedirá la password de nuestro usuario.

- Una vez puesta la pass de nuestro usuario, nos pedirá una **nueva password de root** y que la repitamos.

- Y ya estaría cambiada la **password de nuestro root**.

![alt text](https://user-images.githubusercontent.com/43348980/47658721-bf3e3280-db93-11e8-8d2c-5a86ef26b559.PNG)


Sí por una razón o otra, no te sabes la de **usuario** lo que debemos de hacer es:

 - Iniciamos el ordenador y cuando nos sale el Grub, seleccionamos arrancar en modo recuperación.
 
 - En el submenú que aparece elige "netroot" ("root" en las nuevas versiones), para abrir una terminal como superusuario sin contraseña.
 
 - La partición raíz "/", por defecto, se monta con protección contra escritura, por lo que debemos de volver a montarla con permisos de   lectura y escritura (rw) para poder modificar el sistema: **mount -o remount,rw /**
 
 - Ahora cambia tu contraseña ejecutando el comando: **passwd tu_nombre_usuario**

 - Pulsa Enter y escribe tu nueva contraseña.
 
 - Pulsa enter y te pedirá que la repitas. La escribes de nuevo y vuelve a pulsar Enter.
 
 - Y apaga el sistema y arranca ya con tu usuario y tu contraseña.
