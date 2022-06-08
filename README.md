## LINUX-COMANDOS
##### Allison Elieth Alfaro Leon, Universidad Latinoamericana de Ciencia y Tecnología, ULACIT, 2022
| COMANDO | DESCRIPCION | EJEMPLO |
| ------------ | ------------ | ------------ |
| ps | El comando **ps** muestra por pantalla un listado de los procesos que se están ejecutando en el sistema. | _ps -aux_|
| ps -aux | parametros | ps -aux |
| ps -e |  |  |
| top |  |  |
| htop | El comando **htop** es un visor de procesos interactivo que te permite gestionar los recursos de tu máquina directamente desde el terminal. | _htop_ |
| pstree |  |  |
| man | Muestra la página del manual de cualquier otro comando. | _man ps_ |
| kill -9 | El comando **kill** envía una señal TERM o kill a un proceso que lo termina. Puedes matar procesos introduciendo el PID (ID de los procesos) o el nombre binario del programa. | _kill 533494_ _kill firefox_ |
| ip addr |  |  |
| sudo | Este comando significa **superuser do**, y te permite actuar como superusuario o usuario root mientras ejecutas un comando específico. | _sudo apt install gimp_ |
| apt | Basado en Debian (Ubuntu, Linux Mint). | _sudo apt install transmission_ |
| yum | Basado en Red Hat (Fedora, CentOS). | _sudo yum install transmission_ |
| pacman | Basado en Arch (Manjaro, Arco Linux). | _sudo pacman -S transmission_ |
| sudo apt install openssh-server |  |  |
| && |  |  |
| sudo apt update && sudo apt upgrade |  |  |
| ls | Te permite listar el contenido del directorio que quieras (el directorio actual por defecto), incluyendo archivos y otros directorios anidados. |  |
| ls -l |  |  |
| grep | El comando **grep** busca líneas que coincidan con una expresión regular y las imprime. Puede contar el número de veces que se repite el patrón utilizando el flag -c. | _grep "clase3" semana3.txt_, _grep -c "clase3" semana3.txt_ |
| ps -aux / grep "firefox" |  |  |
| mkdir |  |  |
| pwd |  |  |
| cd, cd .., cd - |  |  |
| cd Allison/ |  |  |
| sudo adduser |  |  |
| sudo userdel |  |  |
| sudo passwd | El comando **passwd** te permite cambiar las contraseñas de las cuentas de usuario. En primer lugar, te pide que introduzcas tu contraseña actual y, a continuación, te pide una nueva contraseña y una confirmación. | _sudo passwd_ |
| sudo passwd root |  |  |
| su |  |  |
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
