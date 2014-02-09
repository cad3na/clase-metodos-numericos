clase-metodos-numericos
=======================

Repositorio con ejemplos vistos en clase de Métodos Numéricos.

Las prácticas de la clase requieren que se tenga instalado el ambiente de desarrollo de IPython.

La manera mas fácil de instalarlo es por medio de la distribución para desarrollo cientifico Anaconda, distribuida libremente en la siguiente [página](https://store.continuum.io/cshop/anaconda/).

## Instalación

1. Descarga el paquete de instalación.
2. Sigue las instrucciones en la pantala.
3. Disfruta!

# Uso del software

El instalador creará accesos directos para las aplicaciones de IPython QT-Console y IPython, pero para ejecutar los archivos de las prácticas tendremos que hacer un poco mas de trabajo que un simple doble clic.

Asegurate de guardar tus prácticas en un solo lugar para facil acceso, como por ejemplo:

    C:\Practicas-Metodos-Numericos

Cuando tengas este directorio en tu sistema abre la aplicacion cmd.exe (en windows 7 es tan simple como apretar la tecla con un simbolo de Windows y escribir '''cmd''' seguido de la tecla Enter), una vez que tengas abierto el simbolo del sistema (nombre raro para una aplicación, lo se) escribe:

    cd Practicas-Metodos-Numericos

y presiona Enter.

Ahora que estamos en el directorio donde has guardado la práctica, puedes invocar el programa escribiendo el comando:

    ipython notebook --pylab inline

Y listo, con esto estarás programando mas rápido de lo que crees.

# Problemas de compatibilidad con las versiones del software

Puede que justo despues de la instalación no tengas la ultima versión de IPython, o alguno de los paquetes necesarios, pero esto se resuelve facilmente.

1. Abre la terminal en Mac o Linux o Simbolo de sistema en Windows (recuerda, tecla de Windows, escribe cmd, Enter).
2. Escribe el comando '''conda update conda''' y presiona Enter.
3. Da un Enter adicional cuando te pregunte si quieres actualizar los paquetes necesarios.
4. Escribe el comando '''conda update ipython matplotlib numpy scipy sympy'''.
5. Da un Enter adicional cuando te pregunte si quieres actualizar los paquetes necesarios.

Con esto obtendrás las versiones mas actuales disponibles del software.

Felices codigos!
