# Readme.md

## Water Mark Remover


### Instalación de Librerías

`pip install pandas`

`pip install pikepdf`

`pip install PyPDF2`


### Padrón Electoral chileno con PyPDF2 + tabula

Recientemente, SERVEL ha incorporado la siguiente marca de agua en el Padrón Electoral chileno:

<img src = "images/WaterMark.png">

La presencia de esta marca de agua, vuelve muy compleja la extracción de la información contenida en el padrón electoral, por lo que realizar análisis sobre estos datos queda supeditado al uso de programas especiales para la extracción de las marcas de agua.

Este cuaderno tiene como objetivo remover esta marca de agua, para eso haremos uso de las librerías: PyPDF2 y pikepdf para el tratamiento de la información contenida en el archivo pdf, y por otra parte tabula y pandas para la extracción de las tablas, almacenaje y la creación de un archivo csv.

Este cuaderno considera la interacción con el usuario, y puede ser empleado en otros contextos distintos al padrón electoral.

Como modelo de juguete, se ha generado un padrón "file_test.pdf" sin nombres reales ni ruts. Pero usted puede acceder al padrón de las elecciones 2021 en el siguiente link: 

`<link>` : <https://www.servel.cl/padron-electoral-definitivo-y-nomina-de-inhabilitados-3>

<img src = "images/WaterMark.png">

En construcción