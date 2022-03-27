# Linux-Solus
# Solus

Solus es una distribución bastante conocida.
Basada en Arch Linux, también es de lanzamiento continuo (rolling release), 
pero al contrario del sistema del que deriva, Solus es muy amigable con el usuario, 
tanto, que recién instalada ya trae todo lo necesario para empezar a usar Steam.
 
 # Instalacion
instalacion paso a paso de Solus.

## 1. Descarga
Descargamos la imagen iso del SO [Solus][1_0] Budgie que pesa aproximadamente 2 Gb

![paginaWeb](img/img_01.png)


[1_0]:https://manjaro.org/downloads/official/xfce/ 

## 2. Maquina Virtual
Para poder instalar el SO vamos a hacer uso la maquina virtual [VirtualBox][1_1]
ya que por medio de esta podemos crear un SO sobre un SO y procedemos a crear la maquina virtual.

[1_1]:https://www.virtualbox.org/

## 2.1 Abrir la maquina virtual
Para acceder a nuestra  maquina virtual, se debe ingresar pormedio de su acceso rapido que se encuentra  nuestro caso en el escritorio            ![VirtualBox][1_2] 

[1_2]:https://www.virtualbox.org/
![img_02](img/img_02.png)

## 2.2 Crear la nueva maquina virtual
Una vez de haber accedido a nuestra maquina virtual, se le debe dar clic en el icono nueva

![img_3](img/img_03.jpg)


## 2.3 Nombre y ubicacion del SO
Organizar en que carpeta desea ubicar la maquina virtual, lo cual por defecto viene 
en una carpeta del mismo software
![img_4](img/img_04.png)

luego de esto presionar "Next".

## 2.4 Tamaño de memoria
Ahora nos aparece una ventana en la cual tenemos que asignar la cantidad de Memoria RAM, esta debe ser determinada por la cantidad de memoria ram que posee nuestro equipo,por ejemplo mi pc posee 8 de Ram, de las cuales 4 se le asignara a este SO.
Esta opcion puede ser por medio de la asignacion de memoria por medio de la barra o para ser muy preciso, se puede hacer manualmente.
![img_5](img/img_05.png)

## 2.5 Disco Duro
Nuesta maquina virtual necesita un disco duro en el que almacenara toda la informacion que manejaremos ahi.
En esta pestaña nos da tres opciones, la primera nos la da para no añadir un disco duro, la segunda es para crear una disco duro
virtual y asi guardar informacion, la tercera y ultima opcion es por si depronto tenemos un archivo que anteriormente por ejemplo
hayamos utilizado como disco duro de otra maquina virtual y lo utilizariamos en la que estamos creando; en este caso le daremos en la segunda opcion
porque crearemos una nuevo.

![img_6](img/img_06.png )

## 2.6 tipo de archivo de disco duro
* [VDI (VirtualBox Disk Image)][2.5.1]: es la selección por defecto,es la imagen de un disco duro virtual
     o el disco lógico asociado con una máquina virtual.
* [VHD (Virtual Hard Disk)][2.5.2]: es la opción a elegir si lo que queremos es crear un disco virtual
 versátil, que podamos recuperar cualquier archivo en su interior fácilmente. Se podrá utilizar
  como unidad de almacenamiento habitual y soporta particiones de todo tipo, como cualquier otro 
  disco duro, además de varios usuarios por cada SO virtual instalado en él. Se utiliza sobre 
  todo para Microsoft Virtual PC.

* [VMDK (VirtualBox Machine Disk)][2.5.2] es el formato típico de VMWare (otro software de virtualización,
    semejante a VirtualBox). Se escogerá esta opción para contar con plena compatibilidad entre 
    VMWare y VirtualBox y poder pasar sistemas operativos virtuales entre ambos softwares
     sin mayor problema.

En nuestro caso marcaremos la primera opcion VDI y presionaremos siguiente.

![img7](img/img_07.png)

[2.5.1]:https://www.techopedia.com/definition/10933/virtual-disk-image-vdi
[2.5.2]:https://megazona.com/software/tipos-de-archivo-de-disco-duro-virtual-en-virtualbox

## 2.7 Almacenamiento de unidad fisica del disco duro
En este punto nos pide seleccionar si queremos nuestro disco duro <b>reservado dinamicamente </b> que solo se usara espacio
en el disco fisico a medida que se llena (hasta un maximo tamaño fijo), sin embargo
no se reducira de nuevo automaticamente cuando el espacio en él se libere o el <b>Tamaño fijo</b> que puede tomar
mas tiempo para su creacion en algunos sistemas, pero normalmente es mas rapido al usarlo.

En nuestro caso utilizaremos la opcion 1 puesto que queremos una candidad especifica para nuestro SO.

![img8](img/img_08.png)

## 2.8 Ubicacion del archivo y tamaño
En este paso se debe crear un disco duro con un minimo de 10GB, porque esto es el requerimiento minimo de este SO.

![img9](img/img_17.png)

seleccionamos la opcion crear para crear nuestra maquina virtual. 


# 3. Configuraciones
una ves creada la maquina virtual, accedemos a las configuraciones de la misma para poder cargar nuestra
imagen iso que descargamos inicialmente; a continuacion mostraremos el paso a paso de la carfa de la imafen iso

## 3.1 Almacenamiento
En las configuraciones siempre nos salen opciones para poder modificar algo que depronto nos haga falta.

en esta ventana nos vamos al apartado de almacenamiento porque aqui es donde vamos a cargar la imagen iso
en una unidad de disco que se crea al momento de hacer el proceso del disco duro 
![img10](img/img_10.png)



## 3.2 Selección del disco
Se selecciona el disco en la cual cargaremos la imagen

![img11](img/img_11.png)

## 3.3 Busqueda
Seleccionamos en nuestros archivos la ubicación de nuestra imagen iso y la seleccionamos

![img12](img/img_12.png)

Posteriormente le damos en "aceptar" para cconfirmar nustra configuracion
![img13](img/img_13.png)

## 3.4 Crear
En este caso se necesita crear otra unidad para, asi que para crearla se necesita hacer lo siguiente
le damos en el controlador IDE y en l¿el icono de disco duro
![img14](img/img_14.png)

luego de eso, si se tiene la unidad ya creada, se selecciona, si no se debe crear con el icono que sale alli
y seguir los mismos pasos desde el punto <b>2.4</b> de este tutorial

![img15](img/img_15.png)

y para finalizarlo, asi quedaria el otro disco creado, en el mismos controlador IDE

![img16](img/img_15.png)



# 4. Ejecutar SO
En este punto ya hemos creado y configurado nuestra maquina virtual con el SO Manjaro,
lo que sigue a continuacion es la ejecucion de de la maquina para ver si fue correctamente creada
![screenshot13](img/screenshot13.jpg)
y si es asi, se abrira un menu en la cual nos da las siguientes opciones
![screenshot14](img/screenshot14.png)
seleccionaremos la opcion "Boot with open source drivers", en este momento nos damos cuenta que 
nuestro SO fue cargado con exito, y procedemos a seleccionar esta opcion para poder tener la distribucion
completa puesto que Linux es un SO libre.

posterior a esto saldra la siguiente ventana que nos da una bienvenida al SO Manjaro 
![screenshot15](img/screenshot15.png)

## 4.1 Configuracion Manjaro
luego de esto procedemos a hacer las configuraciones basicas que tenemos que hacer 
para tener una buena experiencia en el SO.

Inicialmente se nos va a desplegar una ventana en al que esta el paso a paso de las configuraciones,

* iniciamos configurando el origen del equipo.

![screenshot17](img/screenshot17.png)

* Luego seleccionamos el idioma del teclado para utilizar

![screenshot18](img/screenshot18.png)

## Particiones de disco
En la siguiente ventana se presentan 2 opciones, la primera es borrar el disco, basicamente porque recien esta instalando el SO
y la otra es la opcion de conservar la informacion y realizar particiones, en nuestro caso, escogeriamos la segunda,
ya que necesitamos modificarlo

![screenshot19](img/screenshot19.png)

procedemos a hacer las particiones necesarios que cada usuario necesita
en este caso hare 2 partciciones en el primer disco y una sola en el segundo.

aqui nos muestra los Discos que tenemos con posibilidad de modificarlo
![screenshot20](img/screenshot20.png)

primero modificaremos el disco 1, lo seleccionamos y le damos borrar para hacer las particiones desde cero.

![screenshot21](img/screenshot21_LI.jpg)

luego quedara disponible para modificacion toda la unidad, la seleccionamos y le damos crear para hacer 
la primera particion.

Aqui hay que tener algo encuenta, y es que en la primera particion se le pone de tamaño 
la misma cantidad de megas que se puso de memoria RAM al inicio de la instalacion, luego cambiamos la
opcion en sistemas de archivos y lo ponemos en <b>"linuxswap"</b> 

![screenshot23](img/screenshot23.png)

Asignamos el tamaño que queda en la otra particion para el disco, pero aqui hacemos una modificacion
ponemos el sistema de archivos en ext4 y le ponemos como punto de anclaje el <b>root ( / ) </b> que en este 
y le damos siguiente
![screenshot27](img/screenshot27.png)

como en este caso tenemos 2 discos, nos falta modificar el segundo disco y hacemos lo mismo que con el anterior
solo le dejamos todo el tamaño ya que solo sera una particion, y en el punto de anclase le ponemos <b>/home</b> el 
cual sera el almacenamiento de nuestros archivos <b>(en este ejercicio)</b>

![screenshot28](img/screenshot28.png)

para finalizar el area de particiones le damos siguiente (ok)

Siguiendo con la configuracion, nos muestra los datos del usuario, para seguir llenamos las correspondientes
casillas

![screenshot29](img/screenshot29.png)

para casi terminar la congifuracion de Manjaro, nos muestra un resumen de las configuraciones
anteriores que hicimos.
![screenshot30](img/screenshot30.png)

 para terminar le damos en el boton <b>instalar</b> para comenzar el proceso de instalacion

![screenshot32](img/screenshot31.png)


para finalizar, asi estaria el desktop de Manjaro listo para utilizarse.

![screenshot35](img/screenshot35.png)


# Tutotial hecho por:
* Diego Marcelo Jimenez Melendez
* Jhon Fabio España Cortes
* Errol Vladimir Garcia Silva

Universidad De Nariño
