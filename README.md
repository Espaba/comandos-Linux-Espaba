
<p align="center">
:shipit:comandos-Linux-epaniaguab010 :penguin:
</p>

  


    


| Comando | Descripción | Ejemplo |
| ------------- | :-------------: | ------------- |
| man | Mostrar el interfaz del manual con todas sus funciones   | **man man**  para ver las utilidades del paginador del manual  |
| passwd | Cambiar la contraseña | **passwd**  en la terminal de algun usuario para cmabiar la contraseña del mismo |
| whoami | Mostrar nombre de usuarion | **whoami**  en la terminal para ver cuál es el nombre del usuario actual  |
| ip addr  | Mostrar dirreción IP | **ip addr**  para mostrar en consola la dirección IPv4 y la IPv6 |
| apt  | Instalar, eliminar, actualizar software | **apt install**  para instalar algún paquete o aplicación que se necesite |
| sudo | Brindar permiso de administrador | **sudo**  antes de algún comando como **sudo apt install**  para brindar servicios de administrador a la instalación  |
| clear | Limpiar terminal de comandos | **clear** borra todos los comandos que se han escrito hasta el momento en la consola. No elimina el historial de comandos|
| exit | Salir de consola | para salir de la consola se cliquear en la 'x' en la ventana o se puede utilizar el comando **exit** |
| cp | Copiar archivos o directorios | para copiar datos que se encuentren en alguna dirección se escribe **cp + archivo/directorio + nuevo destino**|
| mv | Mover archivos | para mover datos, similar al comando **cp** se escribe **mv + archivo/directorio + nuevo destino**|
| rm | Remover archivos | para ejecutar este archivo simplemente se  escribe **rm** antes del nombre del archivo |
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
| nano | Editar texto | para acceder y ver el contenido de un archivo de texto se puede utilizar el comando **nano + dirección de archivo**. Para editar, se debe presionar la tecla 'insert' y posteriormente proceder a editar. Para salir se utiliza 'Ctrl+x'. | 
| vim | Editar texto | similar a nano, pero cuenta con unas diferencias en aspecto visual y, principalmente, en edición. Para editar un texto con (**vim + dirección del archivo**), se debe simplemente mover al espacio que se desea editar y comenzar a escribir. Para salir, se utiliza el sigo **: + q**. | 

<p align="center">
  <img src="https://user-images.githubusercontent.com/98858991/155067320-9354bf78-61bb-4901-85aa-439bc629593a.gif" alt="animated" />
</p>

