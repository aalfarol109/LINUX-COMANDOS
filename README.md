## LINUX-COMANDOS
### Allison Elieth Alfaro Leon
#### Universidad Latinoamericana de Ciencia y Tecnología-ULACIT
##### 2022
| COMANDO | DESCRIPCION | EJEMPLO |
| ------------ | ------------ | ------------ |
| ps | El comando **ps** muestra por pantalla un listado de los procesos que se están ejecutando en el sistema. | _ps_|
| ps -aux | Esto es una lista estática de información, es decir, es una representación instantánea de los procesos que están en ejecución en el momento de invocar el comando. | _ps -aux_ |
| top | El comando **top** te permite ver las tareas del sistema que se ejecutan en tiempo real. Proporciona un buen resumen de tu sistema para verificar rápidamente si algo se destaca que pueda estar causando problemas con tu sitio web o servidor. | _top_ |
| htop | El comando **htop** es un visor de procesos interactivo que te permite gestionar los recursos de tu máquina directamente desde el terminal. | _htop_ |
| pstree | El comando **pstree** muestra los procesos, desde la línea de comandos, en forma de diagrama de árbol. | _pstree_ |
| man | Muestra la página del manual de cualquier otro comando. | _man ps_ |
| kill -9 | El comando **kill** envía una señal TERM o kill a un proceso que lo termina. Puedes matar procesos introduciendo el PID (ID de los procesos) o el nombre binario del programa. | _kill 533494_ _kill firefox_ |
| ip addr | El comando **ip addr** permite ver las direcciones de interfaz, añadir nuevas direcciones o borrarlas. | _ip addr_ |
| sudo | Este comando significa **superuser do**, y te permite actuar como superusuario o usuario root mientras ejecutas un comando específico. | _sudo apt install gimp_ |
| apt | Basado en **Debian** (Ubuntu, Linux Mint). | _sudo apt install transmission_ |
| yum | Basado en **Red Hat** (Fedora, CentOS). | _sudo yum install transmission_ |
| pacman | Basado en **Arch** (Manjaro, Arco Linux). | _sudo pacman -S transmission_ |
| openssh-server | Recordar: Devices-Network-Bridged Adapter, este comando se utiliza para iniciar el programa cliente SSH que permite la conexión segura al servidor SSH en una máquina. | _sudo apt install openssh-server_ |
| && | Al usar *&&*, el segundo comando se ejecutará solo cuando el primero se haya ejecutado con éxito. | _sudo apt update && sudo apt upgrade_ |
| sudo apt update && sudo apt upgrade | El **update** descarga las listas de paquetes de los repositorios y las “actualiza” para obtener información sobre las versiones más recientes de los paquetes y sus dependencias. El **upgrade** instala paquetes que se agregaron como dependencias de paquetes actualizables.  | _udo apt update && sudo apt upgrade_ |
| ls | Te permite listar el contenido del directorio que quieras (el directorio actual por defecto), incluyendo archivos y otros directorios anidados. | _ls_ |
| ls -l | Agregando la opción **-l** al comando ps se mostrarán distintas informaciones acerca de los procesos actualmente en marcha, incluyendo el estado de cada proceso. Para listar el contenido detallado. | _ls -l_ |
| grep | El comando **grep** busca líneas que coincidan con una expresión regular y las imprime. Puede contar el número de veces que se repite el patrón utilizando el flag -c. | _grep "clase3" semana3.txt_, _grep -c "clase3" semana3.txt_ |
| ps -aux / grep "firefox" | Este comando completo tiene un palito recto en vez de inclinado, lo que realiza es buscar en los procesos el "firefox" | _ps -aux / grep "firefox"_ |
| mkdir | El comando **mkdir** es utilizado para crear un nuevo subdirectorio o carpeta del sistema de archivos.  | _mkdir Allison_ |
| neofetch | El comando **neofetch** es una herramienta CLI (command-line interface) que muestra información sobre tu sistema como la versión del kernel, el shell y el hardware junto a un logotipo ASCII de tu distribución de Linux. | _neofetch_ |
| pwd | El comando **pwd (de las siglas en inglés print working directory, cuya traducción sería imprimir directorio de trabajo)** se utiliza para imprimir el nombre del directorio actual en una sesión de comandos bajo un sistema operativo Unix o derivado. | _pwd_ |
| cd, cd .., cd - | El comando **cd** que significa change directory, **cd** permite moverse entre directorios del sistema. **cd ..** para moverte un directorio por encima de tu posición actual puedes usar el comando cd .., o una secuencia de .. para ir subiendo por la estructura de directorios. **cd -** para regresar al directorio anterior.| cd Allison/ |
| sudo adduser | El comando **adduser** es la versión modificada del comando useradd y facilita la posibilidad de especificar algunos parámetros, como por ejemplo, del usuario a crear y el directorio de inicio (home) para asociarlo. NO USAR MAYUSCULAS EN EL NOMBRE DEL USUSARIO O SALE ERROR. | _sudo adduser test_ |
| sudo userdel | El comando **userdel** modifica los archivos de cuentas de usuario del sistema, eliminando todas las entradas que hacen referencia al nombre de cuenta que vamos a eliminar. | _sudo userdel test_ |
| sudo passwd | El comando **passwd** te permite cambiar las contraseñas de las cuentas de usuario. En primer lugar, te pide que introduzcas tu contraseña actual y, a continuación, te pide una nueva contraseña y una confirmación. | _sudo passwd_ |
| sudo passwd root |  |  |
| su |  |  |
| uname | El comando **uname** imprime la información del sistema operativo, lo que resulta útil cuando se conoce la versión actual de Linux. Se añade un **-a** para mayor informacion. | _uname -a_ |
| whoami | El comando **whoami** (abreviatura de "who am i") muestra el nombre de usuario actualmente en uso. | _whoami_ |
| sudo su |  |  |
| exit |  |  |
| nano |  |  |
| cat | El comando **cat** abreviatura de "concatenate", permite crear, visualizar y concatenar archivos directamente desde el terminal. | _cat semana3.txt_ |
| sudo apt install sl |  |  |
| sudo apt install cowsay |  |  |
| telnet towel.blinkenlights.nl |  |  |
| history | El comando **history** muestra una lista enumerada con los comandos que has utilizado en el pasado | _history_ |
| history > |  |  |
| head -n | El comando **head** muestra las primeras 10 líneas de un archivo de texto, pero puede establecer cualquier número de líneas que desee mostrar con la flag -n. | _head -n 2 semana3.txt_ |
| tail -n | El comando **tail** imprime el contenido de un archivo con una advertencia importante: sólo imprime las últimas líneas. Por defecto, imprime las últimas 10 líneas, pero puedes modificar ese número con -n. | _tail -n 2 semana3.txt_ |
| cp |  |  |
| mv |  |  |
| rm |  |  |
| rm / -R |  |  |
| rm / -Rf |  |  |
| sudo rm / -Rf --no-preserver-root |  |  |
| dpkg |  |  |
| unzip | El comando **unzip** permite extraer el contenido de un archivo .zip desde el terminal.| _unzip imagenes.zip_ |
| alias |  |  |
| unalias |  |  |
| touch | | |
| chmod | | |
| shutdown | El comando **shutdown** te permite apagar tu máquina. Sin embargo, también puede utilizarse para detenerla y reiniciarla. | _shutdown now_ _shutdown 22:30_ |
| shutdown -c | Se utiliza para cancelar un shutdown que se ejecuto anteriormente. | _shutdown -c_ |
