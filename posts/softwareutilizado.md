En el mundo de la programación en Python existen numerosas opciones de IDLE (Integrated Development and Learning Environment) para utilizar. Aunque no existe una opción mejor que otra, después de un poco de análisis terminamos eligiendo unas que nos serían de utilidad por varias razones, siendo una de ellas el trabajo remoto y colaborativo.  

## Python 3.x

Para instalar Python en su versión más nueva deebes visitar este [sitio](https://www.python.org/downloads/). Una vez que se haya descargado se procede a la instalación, teniendo cuidado de seleccionar la opción "Add to path".

Es importante tener en cuenta que al escribir Python en nuestra terminal de Windows, esta nos mandará a la Tienda de Microsoft para instalar python, nosotros no queremos esto.
Para cambiar esto, iremos a Inicio > Configuración > Aplicaciones y Características. 

Buscamos la opción Administrar los alias de ejecución de aplicaciones. Y desactivaremos todos los que sean instaladores de Python. De esta forma al usar el comando Python en nuestra terminal, accederemos correctamente al entorno de python que instalamos desde el navegador.

## Atom

[Atom](https://atom.io) es un IDLE de código abierto y multi-plataforma. Además cuenta con la tecnología [teletype](https://teletype.atom.io) la cual permite hacer edición de código en tiempo real por varios usuarios.

Después de instalar Atom, debemos instalar teletype:
* Esto se puede hace buscando teletype en el buscador de paquetes de Atom y dando click en instalar
* Una vez instalado se da click al botón de la antena de teletype ubicado en la sección inferior derecha del editor
* Debemos conectar nuestra cuenta de GitHub
* Podemos compartir nuestro portal generando un código que podemos compartir, o unirnos usando un código externo


### Otros paquetes que podemos instalar en Atom:
- script: Prmite correr instrucciones dentro de atom (con la excepción que no acepta inputs) [Ctrl + Shift + B]
- python-run-terminalnx: Abre una terminal independiente (acepta inputs) [F5] 
- file-icons: Asigna íconos a los diferentes tipos de archivos (asi se identifica por ejemplo un archivo .py con el ícono de python)
- python-autopep8: Le da formato al código de acuerdo al estilo [PEP8](https://www.python.org/dev/peps/pep-0008/)
- autocomplete-python: Autocompleta con palabras claves de python
- -kite: Permite ver documentación al programar
- linter: Alerta de errores en el código
