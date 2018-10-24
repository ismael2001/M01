**FDISK COMO SE UTILIZA**


**Fdisk** és un comando que nos ayudará en la gestión y administración de nuestro espacio en disco .
Con esta herramienta podremos **crear**, **eliminar**, **redimensionar (restablecer su valor)**, **cambiar o copiar** y **mover particiones**. El límite que existe es de **4 particiones primarias** como máximo por disco.

**COMANDOS BÁSICOS**

- **Para ver todas las particiones**: *fdisk -l*

- **Ver un disco específico**: *fdisk -l /dev/sdb (nombre del disco)*

- **Para ver los comandos en fdisk**: *m para obtener ayuda y ver las opciones que podríamos aplicar al disco*

- **Mostrar toda la tabla de particiones del sistema**: *p para obtener el listado que buscamos*

- **Borrar una partición**: *selecionamos el disco y pulsamos la d de "delete"*

- **Crear una partición**: pulsamos la n de "new", nos pedirá de qué tipo sea (extendida , primaria o swap) para crear una **extendida** pulsaremos la **e**, para crear una **primaria** la **p** y para crear una **swap** la tecla **t**

- **Guardar cambios**: *con la tecla w para escribir los cambios*

- **Formatear una partición**: *mkfs.ext4 /dev/sdb5 (.ext4 que tipo de formato és la partición)*

- **Comprobar el tamaño de la partición**: *con fdisk -s*

