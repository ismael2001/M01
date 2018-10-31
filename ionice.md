**IONICE**

**¿Que es?**

Ionice és un programa que establece un tipo de programación de **io** y una prioridad para un processo, si no se proporciona la suficiente información, con el comando **-p** lo que hace es consultar que tipo de programación y que prioridad tiene para ese processo. 

A partir de eso, el processo puede estar en una de los tres tipos de programación:

- **IDLE**: Este programa se ejecuta con prioridad inactiva solo obtendrá la hora del disco.

- **Best effort**: Es la clase de planificación para cualquier processo que no haya solicitado una prioridad, y és del **0 al 7**.

- **Real Time**: Se le otorga primer acceso al disco, independientemente de lo que ocurra en el sistema. 
