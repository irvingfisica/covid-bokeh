# Taller de visualización de datos, "Visualizando datos de COVID-19"

El objetivo de este taller es mostrar como se van construyendo visualizaciones de datos interactivas usando python y bokeh. 

## Instalar Python, Anaconda, Jupyter Lab, Pandas, Bokeh y todo lo demás...

Para la parte de procesamiento de datos necesitarás instalar [python](https://www.python.org/) y algunas librerías para poder procesar y análizar datos de forma eficiente. 

La forma más fácil de instalar python y las librerías necesarias para analizar datos es a traves de [Anaconda](https://www.anaconda.com/products/individual).

También puedes intalar python por separado siguiendo las instrucciones en su [página](https://www.python.org/downloads/) y luego instalar cada una de las librerías necesarias.

Se puede trabajar con python de muchas maneras. Desde su interprete, desde archivos o scripts. Nosotros trabajaremos con python utilizando Notebooks de [Jupyter](https://jupyter.org/). Estos notebooks nos permiten ejecutar código de forma secuencial y manteniendo los resultados de las ejecuciones anteriores. 

Si instalaste python a traves de Anaconda, el ambiente de trabajo JupyterLab ya se encuentra en tu sistema. Si instalaste python a traves de la página de python o ya lo tenías necesitarás instalar [JupyterLab](https://jupyter.org/install.html).

Para poder analizar y visualizar datos usaremos la librería [Pandas](https://pandas.pydata.org/pandas-docs/stable/index.html) y la librería [Bokeh](https://docs.bokeh.org/en/latest/index.html). Si instalaste todo a traves de Anaconda ya los tienes en tu sistema, si necesitas intalarlos puedes seguir las instrucciones para instalar [Pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/index.html#getting-started) y [Bokeh](https://docs.bokeh.org/en/latest/docs/installation.html).

## Lanzar el Jupyter Lab

Para ocupar JupyterLab necesitas ejecutar el comando "Jupyter Lab" en tu terminal. Si estas en windows e instalaste anaconda tendras una nueva terminal llamada "Anaconda Terminal". Necesitas lanzar el Jupyter Lab desde ahí.

Jupyter Lab se ejecutará en una pestaña de tu explorador. Veras una pantalla similar a esta: 

![Jupyter Lab](./imagenes/img1.png).

Para comenzar un nuevo notebook basta con dar click en el boton "python 3" bajo la sección de Notebooks.

También existen otras maneras de usar lo Notebooks de Jupyter en otros ambientes, por ejemplo con el editor de texto [VSCode](https://code.visualstudio.com/). Solamente necesitas descargarlo e instalar el complemento para python. Una vez que lo abras e instales el complemento puedes abrir un nuevo notebook desde la pantalla de bienvenida al complemento o presionando Ctrl+Shift+P, buscando python en el cuadro de texto disponible y seleccionando: "Python, create new blank jupyter notebook". 

De cualquiera de las dos maneras tendrás un Notebook nuevecito para trabajar, con una celda disponible. A medida que vayas escribiendo y ejecutando código en esta celda aparecerá el resultado de la ejecución y una nueva celda para seguir trabajando.

El resto del tutorial tendrás que teclearla en el notebook que acabas de crear. El resto del tutorial lo encuentras en el archivo "taller_python.ipynb" en este repositorio. Te recomiendo que no solo lo leas, codéalo! No hay manera de aprender a analizar, manipular y visualizar datos si no es haciendolo. El resto del tutorial puedes verlo en el siguiente enlace:

[Enlace a la parte de python del tutorial](https://nbviewer.jupyter.org/github/irvingfisica/covid-bokeh/blob/master/taller_python.ipynb)

