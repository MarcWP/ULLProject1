Actividad 1

Foto del proyecto creado en Unity. Bola con controlador de standard assets y rampa creada con formas cúbicas.

![alt tag](Imagenes/proyectoimag.png)



Actividad 3

En la primera actividad ya se procedió a crear el repositorio requerido. Tras instalar el asset de Github para unity, lo único que era necesario hacer para finalizar era instalar lfs, configurarlo y hacer un push. Para esta actividad, se han decidido señalar a los ficheros fbx para el seguimiento de lfs.

Instalamos lfs y marcamos los ficheros fbx:

![alt tag](Imagenes/proyectoimag3.png)

Hacemos cambios y commit:

![alt tag](Imagenes/proyectoimag4.png)

Hacemos push:

![alt tag](Imagenes/proyectoimag6.PNG)

Como se puede observar, tras el proceso, los ficheros en formato .fbx han sido almacenados con lfs.

![alt tag](Imagenes/proyectoimag7.PNG)



Actividad 4

En esta actividad se procederá a configurar Unity collab. Al carecer de grupo, el único miembro del collab deberé ser yo mismo. 
Para ello, empezaremos seleccionando el botón "Collab" en la zona superior derecha del editor, presionando sobre el borron "Start now!".

![alt tag](Imagenes/proyectoimag8.png)

Seleccionamos un Unity ID. Si no tenemos uno creado, seleccionamos nuestro nombre de usuario y seleccionamos en "Create".

![alt tag](Imagenes/proyectoimag9.png)

Una vez creado el Unity ID, volvemos al botón "Collab" en la zona superior derecha del editor. Si apretamos en "Start now!", Unity comenzará a preparar unestro proyecto para ser utilizado en Unity Collaboration.

![alt tag](Imagenes/proyectoimag10.png)

Una vez finalizado el proceso, podremos empezar a utilizar Unity collab. Como ejemplo, creamos un cubo, guardamos la escena y publicamos los cambios a través de Collab.

![alt tag](Imagenes/proyectoimag11.png)

El proceso tardará en completarse, un función del número de cambios realizados.

![alt tag](Imagenes/proyectoimag12.png)

Al finalizar, los otros miembros deberían recibir un aviso acerca de los nuevos cambios. Si queremos agregar a nuevos participantes, nos basta con seleccionar el icono de grupos en la pestaña de Collab.

![alt tag](Imagenes/proyectoimag13.png)

En la nueva ventana, podremos gestionar los miembros del Collab. Presionamos Manage Seats para invitar a nuevos usuarios.

![alt tag](Imagenes/proyectoimag16.png)

En la zona izquierda, seleccionaremos "Members & Groups".

![alt tag](Imagenes/proyectoimag17.png)

Presionamos en "Add Members"

![alt tag](Imagenes/proyectoimag18.png)

En la nueva ventana introducimos el correo del nuevo participante, seleccionamos su rol y presionamos "Next".

![alt tag](Imagenes/proyectoimag19.png)

Enviamos una invitación al nuevo colaborador haciendo click en "Invite members".

Tras invitar a los nuevos colaboradores, podremos agregarlos a nuestro proyecto de colaboración desde la ventana de gestión de grupos.

![alt tag](Imagenes/proyectoimag14.png)

Tras agregar a los nuevos miembros, se les enviará una invitación que deberán aceptar. Una vez aceptada, podrán descargar el proyecto desde la nube. Una vez dentro del proyecto, serán capaces de visualizar, subir y descargar cambios al proyecto desde la pestaña de Collab en el editor de Unity.

![alt tag](Imagenes/proyectoimag15.png)



Actividad 5

Para la quinta actividad se procederá a configurar una conexión entre un espacio de trabajo de Perforce y un proyecto de Unity. Para ello:

Descargamos e instalamos el servidor Helix Core.

![alt tag](Imagenes/proyectoimag21.png)

Creamos el espacio de trabajo, especificando la ruta a utilizar.

![alt tag](Imagenes/proyectoimag22.png)

Abrimos la conexión.

![alt tag](Imagenes/proyectoimag24.png)

Configuramos la conexión por Perforce a nuestro espacio de trabajo mediante las opciones de nuestro proyecto de Unity.

![alt tag](Imagenes/proyectoimag27.png)

Tras hacer algún cambio en nuestra escena, guardamos y nos dirigimos al panel de Perforce. Bajo la pestaña de cambios pendientes podremos localizar los cambios que hemos realizado a nuestro proyecto.

![alt tag](Imagenes/proyectoimag28.png)

Seleccionamos los cambios pendientes, desplegamos el menú con el click derecho y seleccionamos "enviar". Confirmamos los ficheros a enviar.

![alt tag](Imagenes/proyectoimag29.png)

Podremos encontrar los ficheros modificados en nuestro depot del espacio de trabajo.

![alt tag](Imagenes/proyectoimag30.png)

También podremos localizar dichos cambios en nuestra carpeta de servidor de Perforce.

![alt tag](Imagenes/proyectoimag31.png)