Script para comprobar (usando Python) las direcciones IP bloqueadas por diferentes operadores españoles.
No necesita root

Script
1. Instalar Python (en su sistema operativo o Termux Android)
2. pip install requests datetime ipaddress

Dependiendo de su sistema operativo debe ejecutar el script de una manera o de otra, los resultados se guardan en "resultados.txt" en el mismo directorio donde se encuentra el script.

Puede haber problemas de compatibilidad con Windows (sobre todo en las peticiones), puede solucionarlo usando una maquina virtual que tenga Linux (como Ubuntu o Fedora...)

Añadido nuevos bloques de IP gracias a https://github.com/socram8888/laliga-digi-block-check

Versión 0.0.3

Solo se ha probado correctamente el script para DIGI, no he probado personalmente las versiones para Movistar, Orange, Vodafone ni XtraTelecom
