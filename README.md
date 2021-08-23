# control_movimientos_telescopio
Proyecto para controlar los movimientos de un telescopio via interfaz web
Proyecto para mover en ascension recta y declinacion un telescopio Celestron/SkyWatcher por medio de una interfaz web.
Consta de un programa que monitorea la actividad (en Python 3.7), un modulo en PHP que realiza de interfaz entre la web y el monitor y finalmente el html que realiza la interfaz web.

Funcionamiento:
1) instalar el monitor.py en un directorio, por ejemplo: ~/control_web
2) el control_telescopio.php en el /var/www/html
3) el index.html en /var/www/html
4) crear en /var/www/html una carpeta provi con permisos de lectura/escritura
5) levantar el  control_telescopio.py con el comando: ./control_telescopio.py /dev/ttyUSBXX  (/dev/ttyUSBXX es donde esta conectado el telescopio)
6) levantar el localhost/index.html
7) Disfrute manejando el telescopio vía web !!
