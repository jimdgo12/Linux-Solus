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

![img17](img/img_17.png)

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

![img54](img/img_53.png)
y para finalizarlo, asi quedaria el otro disco creado, en el mismos controlador IDE

![img16](img/img_16.png)



# 4. Ejecutar SO
En este punto ya hemos creado y configurado nuestra maquina virtual con el SO Solus,
lo que sigue a continuacion es la ejecucion de de la maquina para ver si fue correctamente creada y le damos clic en el icono iniciar.
![img19](img/img_19.png)

En este paso se nos abre la interfaz de solus, aqui debemos de darle en la opcion install os
![img20](img/img_20.png)

# 4.1 crear las particiones del primer disco
una vez ingresado en la interfaz nos dirigimos a la parte inferior izquierdo y le damos click en el conjunto de cuadros

![img21](img/img_21.png)

una vez le demos click en los cuadros, se dirigen a la barra de busqueda e ingresamos gparted y le damos clic

![img22](img/img_22.png)

en este punto se puede disponer a crear la particion del dico de 32MG de los discos.
se da click en el boton device y se escoge la opcion

![img23](img/img_23.png)

Se selecciona el tipo de particion y se da clici en el boton apply

![img24](img/img_24.png)

despues de estos pasos se da clic derecho del mouse en la linea de color azul y se escoge la opcion new

![img25](img/img_25.png)
 
 El proximo paso es colocar los valores que aparecen en la imagen y dar click en el boton add

 ![img27](img/img_27.png)

 En el ultimo paso de la particion del disco le damos en la opcion close

  ![img28](img/img_28.png)

  # 4.2 Crear las particiones del segundo disco

  En la esquina superior derecha, desplegamos la lista y escogemos el disco de 4GB

   ![img49](img/img_49.png)

   En este disco se realizan los mismos pasos, solo que se deben colocar los valores que estan en la imagen y se le da click en el boton add

   ![img30](img/img_30.png)

Se continua con los mismos pasos del la particion del primer disco hasta llegar al final y se le da click en el boton cancelar

![img31](img/img_31.png)

# 4.3 Comprobar si fue realizado bien los pasos

A continuacion se presenta la imagen que muestra la configuracion correcta de los pasos

![img32](img/img_32.png)

Continuando con la configuracion se escoge la segunda opcion 

![img33](img/img_33.png)
Se debe realizar la configuracion que se muestra en la imagen

![img34](img/img_34.png)

# 4.4 Configuracion del sistema
aqui se le debe colocar un nombre a la maquina para identificarla en la red

![img35](img/img_35.png)

# 4.5 Datos de la maquina

Aqui se introduce los datos de la persona que utilizara la maquina

![img36](img/img_36.png)

La maquina arroja los datos de ella

![img37](img/img_37.png)

En este punto se le da click en el boton install

![img39](img/img_39.png)

ultimo paso en la configuracion de la particion de los discos y se le da click en el boton restart now

![img40](img/img_40.png)

# Configuracion install os
En esta configuracion es cuando aparece la interfas de solus y se le da click en install os

![img41](img/img_41.png)

Configuracion del idioma y se le da en el boton next

![img42](img/img_42.png)

Se configura la ubicacion y se le da click en el boton next

![img43](img/img_43.png)

Se configura el idioma del teclado y se le da click en el boton next

![img44](img/img_44.png)

Se configura la zona horaria y se le da click en el boton next

![img45](img/img_45.png)

Se debe seleccionar la segunda opcion porque se crearon los discos con sus particiones y se le da click en el boton next

![img46](img/img_46.png)

Se debe dejar igual la configuracion a la imagen y se le da click en el boton next


![img47](img/img_47.png)

Configura el motor de arranque

![img48](img/img_48.png)

se introduce los datos de la persona que utiliza la maquina

![img50](img/img_50.png)

la maquina arroja los datos que ella va a utilizar

![img51](img/img_51.png)

En este punto se da click en el boton install

![img52](img/img_52.png)

En este punto se ha terminado la instalacion del SO linux Solus

![img53](img/img_53.png)

# Tutotial hecho por:
* Diego Marcelo Jimenez Melendez
* Jhon Fabio España Cortes
* Errol Vladimir Garcia Silva

Universidad De Nariño
