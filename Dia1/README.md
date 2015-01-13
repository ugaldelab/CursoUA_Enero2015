#Introducción al Shell
*Basado en http://software-carpentry.org/v5/novice/shell/index.html*

El shell es un interpretador de comandos, que actúa entre el sistema operativo y el usuario. Permite controlar el computador usando una interfaz de linea de comandos, en vez de una visual (GUI, de graphical user interfaces) que ocupa una combinación de mouse y teclado.

Hay varios motivos por los cuales es importante aprender sobre shell:

- La mayoría de los programas bioinformáticos no tienen una interfaz visual. Para el análsis de datos de genómica y metagénomica es necesario usar el shell.
- El trabajo en shell es mas rapido y eficiente. Es posible repetir tareas numerosas veces.
- Muchas veces no es posible analizar los datos en el computador personal, lo que requiere el uso de servidores a los cuales uno se conecta de manera remota.

El principal desafio que presenta el shell es que es principalmente texto, y los comandos y operaciones pueden llegar a ser un poco confusos. Pero solo requiere de práctica!.

## Accediendo al shell

### Windows
Windows no viene con un shell instalado (a diferencia de Linux o Mac), lo cual requiere el uso de programas externos. Hay varios programas que permiten emular un shell en Windows. El que ocuparemos es GitBash (https://msysgit.github.io).

### Linux
Listo!

### Mac
Casi listo. En la carpeta Aplicaciones/Utilidades, abrir la aplicación Terminal.

## Primeros comandos

Vamos a empezar explorando algunos comandos básicos. Al abrir una ventana de shell, debieran ver algo asi:

    $

El simbolo $ es un prompt, que indica que el shell esta esperando por input. Hay variaciones de la información que entrega (a veces se incluye informacion del usuario, directorio, etc), pero siempre esta el simbolo $

Si queremos saber el ID del usuario actual, usamos el comando `whoami`:

    $ whoami
    juan

¿Que esta ocurriendo aquí?. El shell busca el programa que se llama `whoami`, lo ejecuta, muestra la información en la pantalla, y luego queda el shell disponible para ejectuar nuevos comandos.

Otro comando util es `pwd`, que nos permite saber en que directorio estamos ubicados. La salida varía dependiendo de la configuración de cada usuario. Por ejemplo, en mi caso:

    $ pwd
    /Users/juan









