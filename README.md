
<p align="center">
:shipit:comandos-Linux-epaniaguab010 :penguin:
</p>

  


    


| Comando | Descripción | Ejemplo |
| ------------- | :-------------: | ------------- |
| man | Mostrar el interfaz del manual con todas sus funciones   | **man man**  para ver las utilidades del paginador del manual  |
| passwd | Cambiar la contraseña | **passwd**  en la terminal de algun usuario para cmabiar la contraseña del mismo |
| whoami | Mostrar nombre de usuarion | **whoami**  en la terminal para ver cuál es el nombre del usuario actual  |
| echo | Mostrar línea de Strings | si se desea hacer una impresión y ver como luce en consola, se puede utilizar **echo + grupo de Strings**. |
| head -n | Mostrar líneas en archivo | para poder ver cuales son las primeras 'n' líneas de un archivo se ejecuta **head -n3(se quieren ver las primeras 3 líneas) + nombre del archivo**. |
| tail -n | Mostra líneas en archivo | este comando es prácticamente igual al anterior, pero se pueden ver las últimas 'n' líneas de un archivo ejecutando **tail -n3 + nombre del archivo**. |
| ip addr  | Mostrar dirreción IP | **ip addr**  para mostrar en consola la dirección IPv4 y la IPv6 |
| ifconfi | Mostrar dirección IP | similar al comando anterior, ejecutar **ifconfig** en consola muestra información sobre la conexión de red. |
| apt  | Instalar, eliminar, actualizar software | **apt install**  para instalar algún paquete o aplicación que se necesite |
| sudo | Brindar permiso de administrador | **sudo**  antes de algún comando como **sudo apt install**  para brindar servicios de administrador a la instalación  |
| sudo su| Cambiar a modo administrador | si se desea tener siempre el contro de usuario 'root' sin tener que utilizar 'sudo' antes de cada comando, se puede usar el comando **sudo su** y se ingresa la contraseña de usuario(en caso de contar con una). |
| clear | Limpiar terminal de comandos | **clear** borra todos los comandos que se han escrito hasta el momento en la consola. No elimina el historial de comandos|
| history | Mostrar comando digitados | para conocer los últimos comandos que se ejecutaron recientemente, se utiliza el comando **history** |
| exit | Salir de consola | para salir de la consola se cliquear en la 'x' en la ventana o se puede utilizar el comando **exit** |
| cp | Copiar archivos o directorios | para copiar datos que se encuentren en alguna dirección se escribe **cp + archivo/directorio + nuevo destino**|
| mv | Mover archivos | para mover datos, similar al comando **cp** se escribe **mv + archivo/directorio + nuevo destino**|
| rm | Remover archivos | para ejecutar este archivo simplemente se  escribe **rm** antes del nombre del archivo |
| gzip | Comprimir archivos | para comprimir un archivo .txt se puede utilizar el comando **gzip + nombre de archivo**. |
| gunzip | Descomprimir archivos | similar al anterior comando, para descomprimir se utiliza el **gunzip + nombre de archivo**. |
| tar | Comprimir/Descomprimir archivos | Cuando se necesita descomprimir un archivo, por ejemplo, se utiliza el comando **tar -xzf + nombre de archivo**. |
| ln | Enlazar accesos director | si se desea tener un acceso directo de algun archivo o directorio se debe utilizar el comando **ln + dirección(archivo o directorio)**.
| rmdir | Remover directorios | para remover directorios, se ejecuta **rmdir** antes del nombre del directorio |
| mkdir | Crear directorios | para crear un directorio, se debe ejecutar **mkdir + nombre de nuevo directorio** |
| chmod | Cambiar permisos de lectura/escritura/ejecución | Se debe tener conocimiento sobre la tabla de permisos de archivo para jugar con los números binarios. Por ejemplo si se ejecuta **chmod 777 + archivo/directorio** otorga todos los permisos al usuario |
| chown | Cambiar propietario de directorio/archivo | para cambiar la propiedad de un archivo o directorio se ejecuta **chown + propietario:propietario + archivo/directorio** |
| cd | Cambiar de directorio | para poder ejecutar comandos desde algún directorio en específico, se debe ejecutar **cd + directorio** | 
| ls | Mostrar contenido dentro del directorio actual | Si se desea ver el contenido que posee el directorio en que se encuentra, se ejecuta ls |
| ll | Mostrar permisos/propietarios de archivos/directorios | cuando se ejecuta **ll** en el directorio actual, muestra todos los documentos con sus respectivos permisos y propietarios |
| ps | Visualizar procesos | cuando se ejecuta el comando **ps** se muestran todos los procesos que están en ejecución en ese momento |
| ps -aux | Visualizar estados de procesos | similar al comando anterior, ejecutar **ps -aux** muestra los procesos y los estados en que se encuentran |
| df - h| Mostrar el espacio en disco| Ejecutar el comando **df -h** muestra en consola el espacio usado en el disco de almacenamiento |  
| kill -9$PID| Matar un proceso | para 'matar' o eliminar un proceso en ejecución se puede utilizar el comando **kill -9$PID** seguido del nombre del proceso.
| pwd | mostrat el directorio actual | **pwd** significa print working directory y, como su nombre señala, se encarga de imprimir el lugar donde se trabaja en ese momento o directorio |
| curl | Descargar o subir archivos | para descargar un archivo, por ejemplo, se debe ejecutar **curl -o + dirección donde se encuentra el archivo** |
| wget | Descargar archivos desde una URL | para descargar un archvio se utiliza el comando de la siguiente manera **wget + URL de archivo** |
| find | Buscar archivo | si se quiere buscar un archivo en específico, se utiliza el comando **find + directorio + -name + nombre de archivo** |
| grep | Buscar dato o String | similar al comando find, grep permite buscar datos, pero más específicos como Strings. Un ejemplo puede ser **grep + String que se busca + archivo donde se busca** |
| nmap | Brindar información sobre red | al ejecutar el comando **nmap** muestra datos sobre la red a la que se encuentra conectada la máquina; desde direcciones ip hasta puertos abiertos. |
| useradd | Agregar usuarios |  Si se desean agregar usuarios en Linux se puede usar el comando **useradd + nombre de usuario**. |
| passwd | Agregar contraseña | Cuando se desea configurar una contraseña para un usuario, se debe utilizar el comando **passwd + nombre de usuario** |
| touch | Crear archivo | para crear un archivo sin contenido dentro, se puede utilizar el comando **touch + nombre del archivo**.
| cat | Crear archivo | para crear un archivo con contenido, se utiliza el comando **cat + > + nombre de archivo**. Una vez ingresado el comando, se puede comenzar a escribir la información que se desea tener. Para salir del modo escritura, se debe presionar **Ctrl+d**. |
| cat | Concatenar archivos | no solo se utiliza para crear archivos, también se pueden concatenar utilizando el comando **cat + archivo1.txt + > + archivo2.txt**. |
| nano | Editar texto | para acceder y ver el contenido de un archivo de texto se puede utilizar el comando **nano + dirección de archivo**. Para editar, se debe presionar la tecla 'insert' y posteriormente proceder a editar. Para salir se utiliza 'Ctrl+x'. | 
| vim | Editar texto | similar a nano, pero cuenta con unas diferencias en aspecto visual y, principalmente, en edición. Para editar un texto con (**vim + dirección del archivo**), se debe simplemente mover al espacio que se desea editar y comenzar a escribir. Para salir, se utiliza el sigo **: + q**. | 
| uname | Mostrar información de núcleo | si se desea obtener información del kernel, por ejemplo, se debe utilizar el comando **uname** |
| cronab -e | Modificar tiempo de ejecución | **crontab -e** permite modificar el momento en el que se desea ejecutar un script, por ejemplo, con el demonio Cron. | 

<p align="center">
  <img src="https://user-images.githubusercontent.com/98858991/155067320-9354bf78-61bb-4901-85aa-439bc629593a.gif" alt="animated" />
</p>

