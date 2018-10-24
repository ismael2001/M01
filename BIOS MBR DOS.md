**BIOS MBR DOS**

**Viejo** - BIOS MBR DOS **2tb és el tamaño de la partición máximo**

**Nuevo** - UEFI GPT **18 exabytes és el tamaño de la partición máximo**

**MBR DOS**

   ⇩   

**REGLAS**

- Máximo **4** particiones primarias

- **1** de las primarias puede ser **extended**

- Dentro de la extended puede haber **n logicas** (muchas)

- **OBLIGATORIO**: Una primaria debe ser **Active**       

   Una **no extended** no puede ser **Active**
   
   **Linux** - Para arrancar no importa una **primaria activa**
   
   **Windows** - Para arrancar requiere una partición **primaria activa**
   
   **TIP**: Instala Win en cualquier partición siempre que tenga **primaria activa**, "hace falta **100mb** para poder instalar Win."
   
   **Mentira** - No hace falta que sea de **100mb** para poder instalar un Windows
   
   **BOOTMGR** - **WINDOWS**
   
   **GRUB** - **LINUX**
  
  
  **UEFI GPT** - **GUID PARTITION TABLE** "no hay primarias, activas..."
  
  Para cambiar a **MBR** se entra en la **bios** y ponemos el **modo legacy** y al contrario si queremos poner **GPT** cambiamos el modo a **UEFI**.













