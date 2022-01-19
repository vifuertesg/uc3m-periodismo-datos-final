## Examen Periodismo de Datos (19/01/2022)
##### Victoria Fuertes González

**100. ¿Quién es Philip Meyer?**

**101. ¿Quién fue Florence Nightingale?**
Florence Nightingale (1820 -1910)fue una enfermera, escritoria y estadística, considerada pionera de la enfermería moderna, creando el primer modelo conceptual de enfermería.

**1. ¿Qué es el periodismo de datos? Aporta tus impresiones sobre el debate.**

**4. ¿Qué medio de comunicación inglés es fundamental en el periodismo y la visualización de datos?**
El medio británico *The Guardian* es uno de los medios pioneros en el periodismo de datos moderno.   

**5. Qué lenguajes informáticos conoces. Razona la respuesta.**

**6. Cuál es la diferencia entre Internet y la Web. Razona la respuesta.**
Internet es una red de redes, es decir,  una red de computadoras de todo el mundo, un sistema de computadoras conectadas a nivel global. Y por otro lado, la web es una colección de páginas que se asienta sobre esta red de computadoras de internet, la web funciona a través de internet y sirve para transmitir datos. 

**7. ¿Qué fue determinante para el nacimiento del periodismo de datos moderno?**
Entre el año 2006 y 2008 nació el periodismo de datos moderno y apareció por la combinación de varios factores: la abundancia de software de datos abiertos, HTML5 y Open Data. De esta forma estos tres elementos fueron los detonantes de su nacimiento.

**8. Qué saberes están implicados en periodismo de datos. Razona la respuesta.**
En el periodismo de datos nos encontramos con tres áreas o saberes implicados, ya que al ser una disciplina nueva, también es una disciplina contenedor. Estos saberes son:
*El periodismo*, el cual solo puede existir si hay investigación.*Los datos*, que se definen como registros electrónicos que han de ser tratados por ordenador. *La visualización de datos:* desde la Web hasta el papel pasando por la estadística.

**15. Cuál fue el comienzo del CAR (Computer Assisted Reporting)?**



**45. Pon un ejemplo de uso de "wildcards"**
A la hora de listar, copiar, mover y otras operaciones se pueden usar las wildcards o comodines. Las máscaras wildcard utilizan unos y ceros binarios para filtrar direcciones IP individuales o grupos de direcciones IP para permitir o denegar el acceso a los recursos. 
Por ejemplo, si tengo una carpeta en mi archivo de nombre data y dentro de ella tengo archivos csv, json y xls, todos en la misma carpeta. Y quiero organizar estos archivos según su tipo, crearía unas carpetas que se llamarán csv, json y xls dentro de data. Me situaría en el directorio data con el comando cd: cd ~/Escritorio/data. Crearía las carpetas con mkdir: mkdir csv json xls. Movería los archivos con mv: mv *.json json/, y luego con los otros dos tipos de archivos.

**52. ¿Cómo ves todos los dialectos de la shell disponibles?**
Usando el comando cat (que permite ver contenido), de tal forma que escribo desde la terminal: cat /etc/shells

**53. Pon un par de ejemplos de Google Dorks u "operadores de búsqueda"**
1. **$** Sirve para buscar precios. También funciona para el Euro (€), pero no para la Libra Esterlina (£). Ejemplo: ipad $ 329
2. **define:** Es un diccionario integrado en Google, básicamente. Esto mostrará el significado de una palabra en un resultado similar a una tarjeta en las SERPs. Ejemplo: define:entrepreneur

**54. Cómo realizas algún cambio en tu repositorio local y lo actualizas también en Github. Explica los pasos.**
Utilizando **nano** o cualquier otro editor de texto cambiamos algo, guardamos, cerramos y seguimos tres pasos para actualizar los cambios en github:
- git add nombre-archivo-cambiado
- git commit -m "comentario del cambio"
- git push main origin

**55. Explica los pasos para clonar en tu ordenador un repositorio de Github.**
Voy a la carpeta de mi elección con el comando cd y escribo git clone seguido de la dirección de nuestro repositorio git en github (el que queremos clonar). 
Si no es la primera vez que hacemos esto, simplemente tendría que ponerme dentro de la carpeta y actualizar con git pull.
