.. _Ingreso:

Ingreso
=======

Qué es SSH
####################
El nombre SSH viene de Secure SHell, y es un protocolo que permite acceder de manera remota a un servidor por medio de un canal encriptado, por lo que las comunicaciones mendiante este protocolo suelen ser las más comunes para acceder a servidores, especialemente aquellos con sistema operativo GNU Linux.

Instalar un cliente SSH
####################

Para acceder al HPC del CECC usted debe hacer hacerlo mediante el uso de SSH, por lo que va a requerir un cliente SSH. Si usted posee una computadora algúna distribución de `GNU/Linux <https://www.gnu.org/home.es.html>`_ o  `MacOS (Antes OSX) <https://www.apple.com/co/macos/monterey/>`_, su computadora ya cuenta con un cliente SSH instalado en la terminar y puede pasar a la siguiente sección. En caso de utilizar una computadora con `Windows <https://www.microsoft.com/es-xl/windows>`_ será necesario intslara un cliente SSH ya que su sistema operativo no cuenta con uno instalado por defecto, a continuación le mostraremos algunos clientes SSH que puede intalar en Windiws.

Clientes SSH para windows:
************************

`MobaXterm <https://mobaxterm.mobatek.net/download.html>`_

.. image:: /images/Moba.png
    :width: 600px
    :align: center
    :height: 331px
    :alt: MobaXterm image
    
MobaXterm es un toolbox para computación remota, cuenta con un clientes SSH bastante completo y otras caracteristicas adicionales como multi ejecución (ejecutar el mismo codigo en varios servidores a la vez), compatibilidad con X11 Server,etc. 


`PuTTY <https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html>`_

.. image:: /images/Putty.PNG
    :width: 452px
    :align: center
    :height: 442px
    :alt: PuTTY image

Putty es un clientes SSH con varias herramientas como creación de llaves SSH, compatibilidad con IPv6, etc. Este cliente es más ligero que MobaXterm por lo que es una buena alternativa en caso de que el usuario cuente con una maquina con recursos limitados. 

Conectarse usando SSH
################

MacOS y GNU/Linux
******************

Para conectarse usando MacOS o GNU/Linux , deberá abrír la terminal y escribir el comando *SSH* seguido de *dirección IP @ su usuario* usando la dirección IP del HPC del CECC como se muestra en la imagen: 

.. image:: /images/linux1.png
    :width: 600px
    :align: center
    :height: 325px
    :alt: Linux terminal image

Si ha seguido los pasos correctamente, tendá acceso al HPC del CECC.  

Windows
**********
**Conectarse usando PuTTY**


Una vez abierto el programa aparecerá el siguiente menú:

.. image:: /images/Putty.PNG
    :width: 452px
    :align: center
    :height: 442px
    :alt: Putty tutorial
 

En este menú deberá ingresar la dirección IP HPC del CECC y seleeciónar el tipo de conexión *SSH*

.. image:: /images/Putty/Putty.PNG
    :width: 452px
    :align: center
    :height: 442px
    :alt: Putty tutorial
    
    
Una vez de click en *Open*, la primera vez que se conecte a cualquier sevidor aparecerá una ventana como la que se muestra a continuacón (esto es totalmente normal y tiene como objetivo que su computador guarde un identificador para que la proxima vez que usted se trate de conectar al sevidor usando la misma dirección IP su computadora pueda verificar que es el mismo al que se conecto previamente), para continuar solo de click en *Accept*.    

.. image:: /images/Putty/putty1.PNG
    :width: 611px
    :align: center
    :height: 418px
    :alt: Putty tutorial


Ahora saldrá está ventana donde se le pedira que ingresé el usuario y contraseña que el administrador le haya suministrado: 

.. image:: /images/Putty/putty2.PNG
    :width: 611px
    :align: center
    :height: 418px
    :alt: Putty tutorial
   
   
Si ha seguido los pasos correctamente, tendá acceso al HPC del CECC.    


**Conectarse usando MobaXterm:**

Una vez abierto el programa aparecerá el siguiente menú:

.. image:: /images/Moba.png
    :width: 600px
    :align: center
    :height: 331px
    :alt: MobaXterm tutorial


En este menú deberá dar click en el botón de sesiones: 

.. image:: /images/Moba/Moba.PNG
    :width: 901
    :align: center
    :height: 503
    :alt: MobaXterm tutorial


Cuando vez oprima dicho botón, aparecerá un menú donde debrá seleccionar el tipo protocolo que desea usar, en este caso deber seleccionar *SSH*: 

.. image:: /images/Moba/Mobases.PNG
    :width: 600
    :align: center
    :height: 402
    :alt: MobaXterm tutorial


Una vez seleccionado SSH, aparecerá un recuadro donde deberá introducir la dirección IP del HPC del CECC

.. image:: /images/Moba/mobases2.PNG
    :width: 600
    :align: center
    :height: 403
    :alt: MobaXterm tutorial
 
 
Despues de haber introducido la dirección IP, saldrá este recuadro donde se le pedira que ingresé el usuario y contraseña que el administrador le haya suministrado: 

.. image:: /images/Moba/mobases4.PNG
    :width: 600
    :align: center
    :height: 334
    :alt: MobaXterm tutorial
 


Si ha seguido los pasos correctamente, tendá acceso al HPC del CECC.  
