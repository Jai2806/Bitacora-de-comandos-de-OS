**Jailynne Dayanne Acuña Corrales**
**Universidad Latinoamericana de Ciencia y Tecnología**
**ULACIT**
**2022**

sudo ./VBoxLinuxAdditions.run

man ps (manual de un comando)

ps -aux(Procesos)

ps -aux | grep "firefox" (| concatena dos comcandos)

ps -aux | grep + "lo que se quiere buscar" (busca archivos en especìfico (filtro))

top (procesos)

Ctrl+c (salirse de algùn comando)

pstree (àrbol de procesos)

matar un proceso (por process ID) KIll -9 (+process ID)

IP ( IP ADDR) 10.200.0.147

sudo apt install (instalar paquete)

ls (listar contenido de una carpeta)

ls -l (Ver carpetas)

mkdir + nombre de la carpeta (crear carpetas)

pwd (muestra ruta de archivos)

cd (moverse entre directorios

sudo adduser (crear un usuario nuevo)

sudo passwd + nombre del usuario (cambiar contraseña)

sudo userdel + nombre del usuario (borrar usuario)

su + nombre del usuario (cambia a otro usuario, loggearse)

whoami (ver cuàl usuario està logeado)

exit (cerrar sesiòn)

sudo su (loggin como admin)

clear (limpia termial)

nano (ver archivos de texto)

nano + nombre del archivo (modo ediciòn)

cat + nombre del archivo (ediciòn del archivo)

sl (trensito)

cowsay (Vaca hablando)

sudo apt install cowsay (installar vaca)

history (ver historial de comandos)

telnet towel.blinkenlights.nl (ver capitulo de Star Wars)

history > + nombre del archivo (guardar el historico de los comandos)

head -n + numero de lineas + nombre del archivo (principio)

tail -n 3 semana3.txt (buscar solo el final)

tail -n 3 semana3.txt > finsemana3.txt

cat semana3.txt | more (muestra el archivo de historia a pocos)

ps - aux | more

cp + nombre del archivo + ubicacion(copiar un archivo)

cp semana3.txt JAI

mv + nombre del archivo + ubicacion(copiar un archivo)

mv semana3.txt JAI

rm + nombre de archivo (borrar)

rm + nombre de ubicaciòn/ -r (borrar directorios)

rm / -RF (echarsela)

dpkg -i + archivo dp que se quiere instalar (instalar un paquete que se haya descargado)


alias listar="+nombre del comando" (Cambiar nombres al comando)

--DOCKER--
-d (Modo Detached)

-p (Abrir un puerto)
(OKATETA)

--Comandos--

chmod (otorgar permisos a un archivo)
sudo chmod +wrx (agregar permisos a un archivo de un usuario específico.) 
du -h (de qué tamaño es un archivo)
stat + nombre del archivo (info completa del archivo)
file + nombre del archivo (de qué formato es un archivo)
df - h (Muestra el espacio de los HD instalados)
sudo apt install gparted (Administra HD)
sudo ./VBoxLinuxAdditions.run

man ps (manual de un comando)

ps -aux(Procesos)

ps -aux | grep "firefox" (| concatena dos comcandos)

ps -aux | grep + "lo que se quiere buscar" (busca archivos en especìfico (filtro))

top (procesos)

Ctrl+c (salirse de algùn comando)

pstree (àrbol de procesos)

matar un proceso (por process ID) KIll -9 (+process ID)

IP ( IP ADDR) 10.200.0.147

sudo apt install (instalar paquete)

ls (listar contenido de una carpeta)

ls -l (Ver carpetas)

mkdir + nombre de la carpeta (crear carpetas)

pwd (muestra ruta de archivos)

cd (moverse entre directorios

sudo adduser (crear un usuario nuevo)

sudo passwd + nombre del usuario (cambiar contraseña)

sudo userdel + nombre del usuario (borrar usuario)

su + nombre del usuario (cambia a otro usuario, loggearse)

whoami (ver cuàl usuario està logeado)

exit (cerrar sesiòn)

sudo su (loggin como admin)

clear (limpia termial)

nano (ver archivos de texto)

nano + nombre del archivo (modo ediciòn)

cat + nombre del archivo (ediciòn del archivo)

sl (trensito)

cowsay (Vaca hablando)

sudo apt install cowsay (installar vaca)

history (ver historial de comandos)

telnet towel.blinkenlights.nl (ver capitulo de Star Wars)

history > + nombre del archivo (guardar el historico de los comandos)

head -n + numero de lineas + nombre del archivo (principio)

tail -n 3 semana3.txt (buscar solo el 
final)

tail -n 3 semana3.txt > finsemana3.txt

cat semana3.txt | more (muestra el archivo de historia a pocos)

ps - aux | more

cp + nombre del archivo + ubicacion(copiar un archivo)

/
Funciona para que se pueda ver en root el home del usuario antes mencionado.

/bin
Es un directorio estático y es donde se almacenan todos los binarios necesarios para garantizar las funciones básicas a nivel de usuario.

/boot
Contiene los archivos que se utilizan para arrancar el sistema operativo.

/dev
Este directorio incluye todos los dispositivos de almacenamiento, en forma de archivos, conectados al sistema y que el sistema pueda entender como un volumen lógico de almacenamiento.

/etc
Su propósito es almacenar varios archivos de configuración de todo el sistema.

/home
Es el directorio de los usuarios estándar, y, por lo tanto, el destinado a almacenar todos los archivos del usuario.

/lib
Se utiliza para bibliotecas de terceros. Es decir, se utilizan para asegurar de que se coloca el código escrito de otro autor o equipo de desarrolladores en un lugar que se pueda recuperar fácilmente y atribuir, en un proyecto.

/media
Representa el punto de montaje de todos los volúmenes lógicos que se montan temporalmente.

/mnt
Se utiliza para puntos de montaje temporales que el usuario puede crear manualmente.

/opt 
Van todos aquellos archivos de solo lectura que son parte de programas auto-contenidos y que, por lo tanto, no siguen los estándares de almacenar los diferentes archivos dentro de los diferentes subdirectorios de /usr.

/proc
Este directorio contiene información de los procesos y aplicaciones que se están ejecutando en un momento determinado en el sistema, pero realmente no guarda nada como tal, ya que lo que almacena son archivos virtuales, por lo que el contenido de este directorio es nulo.

/root
Es el directorio /home del usuario root o superusuario del sistema. el directorio del usuario root está en su propia carpeta colgando directamente de la raíz del sistema.

/sbin
Es un directorio estático y es donde se almacenan todos los binarios relativas tareas propias del sistema operativo, y que solamente pueden ser gestionadas por el usuario root, tales como el arranque, tareas de restauración, reparación, etc.

/run
Funciona para ejecutar algún aplicativo instalado en el OS.

/srv
Sirve para almacenar archivos y directorios relativos a servidores que puedan estar instalados dentro del sistema.

/sys 
Contiene archivos virtuales que proveen información del kernel relativa a eventos del sistema operativo.

/tmp
Sirve para almacenar archivos temporales de todo tipo.

/usr
Actualmente sirve para almacenar todos los archivos de solo lectura y relativos a las utilidades de usuario, incluyendo todo el software instalado a través de los gestores de paquetes de cada distribución. Contiene los siguientes subdirectorios:
/usr/bin
/usr/include
/usr/lib
/usr/local
/usr/sbin
/usr/share
/usr/src

/var 
Contiene varios archivos con información del sistema, como archivos de logs, emails de los usuarios del sistema, bases de datos, información almacenada en la caché, información relativa a los paquetes de aplicaciones almacenados en /opt, etc. 
cp semana3.txt JAI

mv + nombre del archivo + ubicacion(copiar un archivo)
mv semana3.txt JAI

rm + nombre de archivo (borrar)

rm + nombre de ubicaciòn/ -r (borrar directorios)

rm / -RF (echarsela)

dpkg -i + archivo dp que se quiere instalar (instalar un paquete que se haya descargado)


alias listar="+nombre del comando" (Cambiar nombres al comando)

TESTDISK (Recupera archivos en Ubuntu)
Información del sistema
arch: mostrar la arquitectura de la máquina (1).
uname -m: mostrar la arquitectura de la máquina (2).
uname -r: mostrar la versión del kernel usado.
dmidecode -q: mostrar los componentes (hardware) del sistema.
hdparm -i /dev/hda: mostrar las características de un disco duro.
hdparm -tT /dev/sda: realizar prueba de lectura en un disco duro.
cat /proc/cpuinfo: mostrar información de la CPU.
cat /proc/interrupts: mostrar las interrupciones.
cat /proc/meminfo: verificar el uso de memoria.
cat /proc/swaps: mostrar ficheros swap.
cat /proc/version: mostrar la versión del kernel.
cat /proc/net/dev: mostrar adaptadores de red y estadísticas.
cat /proc/mounts: mostrar el sistema de ficheros montado.
lspci -tv: mostrar los dispositivos PCI.
lsusb -tv: mostrar los dispositivos USB.
_date: mostrar la fecha del sistema.
cal 2011: mostrar el almanaque de 2011.
cal 07 2011: mostrar el almanaque para el mes julio de 2011.
date 041217002011.00: colocar (declarar, ajustar) fecha y hora.
clock -w: guardar los cambios de fecha en la BIOS.
Apagar (Reiniciar Sistema o Cerrar Sesión)
shutdown -h now: apagar el sistema (1).
init 0: apagar el sistema (2).
telinit 0: apagar el sistema (3).
halt: apagar el sistema (4).
shutdown -h hours:minutes &: apagado planificado del sistema.
shutdown -c: cancelar un apagado planificado del sistema.
shutdown -r now: reiniciar (1).
reboot: reiniciar (2).
logout: cerrar sesión.
Archivos y Directorios
cd /home: entrar en el directorio “home”.
cd ..: retroceder un nivel.
cd ../..: retroceder 2 niveles.
cd: ir al directorio raíz.
cd ~user1: ir al directorio user1.
cd –: ir (regresar) al directorio anterior.
pwd: mostrar el camino del directorio de trabajo.
ls: ver los ficheros de un directorio.
ls -F: ver los ficheros de un directorio.
ls -l: mostrar los detalles de ficheros y carpetas de un directorio.
ls -a: mostrar los ficheros ocultos.
ls [0-9]: mostrar los ficheros y carpetas que contienen números.
tree: mostrar los ficheros y carpetas en forma de árbol comenzando por la raíz.(1)
lstree: mostrar los ficheros y carpetas en forma de árbol comenzando por la raíz.(2)
mkdir dir1: crear una carpeta o directorio con nombre ‘dir1’.
mkdir dir1 dir2: crear dos carpetas o directorios simultáneamente (Crear dos directorios a la vez).
mkdir -p /tmp/dir1/dir2: crear un árbol de directorios.
rm -f file1: borrar el fichero llamado ‘file1’.
rmdir dir1: borrar la carpeta llamada ‘dir1’.
rm -rf dir1: eliminar una carpeta llamada ‘dir1’ con su contenido de forma recursiva. (Si lo borro recursivo estoy diciendo que es con su contenido).
rm -rf dir1 dir2: borrar dos carpetas (directorios) con su contenido de forma recursiva.
mv dir1 new_dir: renombrar o mover un fichero o carpeta (directorio).
cp file1: copiar un fichero.
cp file1 file2: copiar dos ficheros al unísono.
cp dir /* .: copiar todos los ficheros de un directorio dentro del directorio de trabajo actual.
cp -a /tmp/dir1 .: copiar un directorio dentro del directorio actual de trabajo.
cp -a dir1: copiar un directorio.
cp -a dir1 dir2: copiar dos directorio al unísono.
ln -s file1 lnk1: crear un enlace simbólico al fichero o directorio.
ln file1 lnk1: crear un enlace físico al fichero o directorio.
touch -t 0712250000 file1: modificar el tiempo real (tiempo de creación) de un fichero o directorio.
file file1: salida (volcado en pantalla) del tipo mime de un fichero texto.
iconv -l: listas de cifrados conocidos.
iconv -f fromEncoding -t toEncoding inputFile > outputFile: crea una nueva forma del fichero de entrada asumiendo que está codificado en fromEncoding y convirtiéndolo a ToEncoding.
find . -maxdepth 1 -name *.jpg -print -exec convert ”{}” -resize 80×60 “thumbs/{}” ;: agrupar ficheros redimensionados en el directorio actual y enviarlos a directorios en vistas de miniaturas (requiere convertir desde ImagemagicK).
Encontrar archivos
find / -name file1: buscar fichero y directorio a partir de la raíz del sistema.
find / -user user1: buscar ficheros y directorios pertenecientes al usuario ‘user1’.
find /home/user1 -name *.bin: buscar ficheros con extensión ‘. bin’ dentro del directorio ‘/ home/user1’.
find /usr/bin -type f -atime +100: buscar ficheros binarios no usados en los últimos 100 días.
find /usr/bin -type f -mtime -10: buscar ficheros creados o cambiados dentro de los últimos 10 días.
find / -name *.rpm -exec chmod 755 ‘{}’ ;: buscar ficheros con extensión ‘.rpm’ y modificar permisos.
