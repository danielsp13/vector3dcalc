# Vector 3D Calc

## Una calculadora gráfica sencilla con Python

*Autor: Daniel Pérez Ruiz*



### Descripción general

**Vector 3D Calc** es una calculadora de operaciones con vectores tridimensionales. Esta totalmente desarrollada con **Python**, incluyendo su interfaz gráfica.

****

### Licencia

Esta calculadora está distribuida bajo la licencia **[GNU, General Public License v3](LICENSE)**, que permite:

* **Libertad de uso.** Los usuarios tienen la libertad de estudiar, modificar y distribuir el software.
* **Distribución del código fuente.** Cualquier distribución del software debe incluir el código fuente completo del programa, junto con cualquier modificación realizada.
* **Compatibilidad con versiones anteriores.** Los programas distribuidos bajo versiones anteriores de la licencia GPL, pueden ser actualizados a GPL v3 si el autor así lo elige.
* **Derivados bajo la misma licencia.** Si alguien modifica el software distribuido bajo esta licencia, está obligado a hacerlo bajo los términos de GPLv3.
* **Protección de libertades de los usuarios.**
* **Cobertura internacional.**

****

### Requisitos para usar el proyecto

Para poder ejecutar adecuadamente el proyecto, debe satisfacer los siguientes requisitos:

1. Tener instalado el intérprete de **Python** en su sistema operativo. Se recomienda utilizar la *última versión disponible, ([véase aquí](https://devguide.python.org/versions/#versions))*, pero como mínimo se acepta la versión **3.10**. Puede descargar Python para su sistema [aquí](https://www.python.org/downloads/).
2. Tener instalado **pip**, que es un gestor de módulos del lenguaje. Compruebe que lo tenga instalado con la orden `pip --help`, y en caso de error, consulte [las instrucciones oficiales de instalación](https://pip.pypa.io/en/stable/installation/).

****

### Órdenes de instalación y verificación

Para poder ejecutar el proyecto, necesita instalar el **[gestor de dependencias](https://python-poetry.org/)** y el **[gestor de tareas](https://github.com/nat-n/poethepoet)** definido para este proyecto. Utilice la siguiente orden:

~~~bash
$ pip install poetry poethepoet
~~~

Para comprobar que todo funciona correctamente pruebe a ejecutar las siguientes órdenes:

~~~bash
$ poetry --help
~~~

~~~bash
$ poe --help
~~~

En caso de que estas órdenes no funcionen, es recomendable que incluya `poetry` y `poe` en su variable de entorno [PATH](https://es.wikipedia.org/wiki/PATH_(inform%C3%A1tica)). En sistemas Linux puede hacerlo así:

~~~bash
$ export PATH="$HOME/.local/bin:$PATH"
~~~

Además, puede añadir esta última linea en el archivo de configuración de su terminal (en el caso de bash), es inlcuirlo en `.bashrc`.



#### Crear entorno virtual e instalar dependencias de proyecto

A continuación, debe crear el [entorno virtual](https://www.freecodecamp.org/espanol/news/entornos-virtuales-de-python-explicados-con-ejemplos/) que contendrá de forma aislada todas las dependencias requeridas para el proyecto. El gestor de tareas se encargará por usted de hacerlo, y para ello, ejecute la siguiente orden.

~~~bash
$ poe install
~~~

