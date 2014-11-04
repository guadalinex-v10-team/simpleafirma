simpleafirma
============

Aplicación independiente "Firma Fácil" lanzable desde el navegador mediante urls afirma:// 

Copyright (c) 2014 Gobierno de España <soporte.afirma5@minhap.es>


NOTAS:

- El paquete instala la aplicación y define los handlers para que Firefox detecte las urls que comiencen por afirma: y lance automáticamente el programa simpleafirma
- Debido a un bug aparecido en Firefox desde la versión 22, los nuevos manejadores de urls (como afirma:) son detectados, pero el programa que debería lanzarse no aparece automáticamente. Está corregido en la versión 31 (https://bugs.launchpad.net/ubuntu/+source/firefox/+bug/1197559). Si se utiliza una de estas versiones de Firefox, el usuario deberá elegir el programa simpleafirma manualmente la primera vez que acceda a una url afirma:
