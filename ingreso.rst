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
    :width: 911px
    :align: center
    :height: 523px
    :alt: Estructura CECC
    
MobaXterm es un toolbox para computación remota, cuenta con un clientes SSH bastante completo y otras caracteristicas adicionales como multi ejecución (ejecutar el mismo codigo en varios servidores a la vez), compatibilidad con X11 Server,etc. 



`PuTTY <https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html>`_

.. image:: /images/Putty.PNG
    :width: 452px
    :align: center
    :height: 442px
    :alt: Estructura CECC

Putty es un clientes SSH con varias herramientas como creación de llaves SSH, compatibilidad con IPv6, etc. Este cliente es más ligero que MobaXterm por lo que es una buena alternativa en caso de que el usuario cuente con una maquina con recursos limitados. 

Conectarse usando SSH
################

MacOS y GNU/Linux
******************

Windows
**********

Conectarse usando MobaXterm:

Una vez abierto el programa aparecerá el siguiente menú:

.. image:: /images/Moba.PNG
    :width: 911px
    :align: center
    :height: 523px
    :alt: Estructura CECC

En este menú deberá dar click en el botón de sesiones: 

.. image:: /images/Moba/Moba.PNG
    :width: 901
    :align: center
    :height: 503
    :alt: Estructura CECC

Una vez oprima dicho botón, aparecerá un menú donde debrá seleccionar el tipo protocolo que desea usar, en este caso deber seleccionar SSH: 

.. image:: /images/Moba/Mobases.PNG
    :width: 898
    :align: center
    :height: 604
    :alt: Estructura CECC
    
Una vez seleccionado SSH, aparecerá un recuadro donde deberá introducir la dirección IP del HPC del CECC

.. image:: /images/Moba/Mobases2.PNG
    :width: 898
    :align: center
    :height: 604
    :alt: Estructura CECC
  
 
