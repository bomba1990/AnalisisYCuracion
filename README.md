# Analisis Exploratorio Y Curación de Datos

Repositorio para la materia de Análisis Exploratorio y Curación de Datos de #DiploDatos de FaMAF - UNC. Más info en esta [página](http://diplodatos.famaf.unc.edu.ar/analisis-y-curacion-de-datos/)

## Contenido

* Filminas en pdf
* Datos de práctico (carpeta `input`):
    * `wtageinf.csv`: datos para el ejercicio de tablas de peso
    * `pasos.json`: datos para el ejercicio de pasos por provincia
    * `kickstarter-projects/`: datos para los ejercicios de limpieza
* Notebooks de práctico (carpeta notebooks):
    * `Limpieza.ipynb`: Checklist y ejercicios de limpieza de datos
    * `Ejercicio-tablas.ipynb`: Ejercicio de tablas de peso

## Cómo correr los notebooks

Los notebooks corren:

* con Jupyter Stacks (probado)

        docker run -p 8888:8888  -v $(pwd):/home/jovyan/work jupyter/scipy-notebook

* con [Anaconda](https://www.anaconda.com/distribution/) (probado en Linux con anaconda=2019.03)
* con [Colab](https://colab.research.google.com/) agregando la ruta del notebook a github (probado al 3/5/2019):
    * Limpieza: https://colab.research.google.com/github/DiploDatos/AnalisisYCuracion/blob/master/notebooks/Limpieza.ipynb
    * Ejercicio-tablas: https://colab.research.google.com/github/DiploDatos/AnalisisYCuracion/blob/master/notebooks/Ejercicio-tablas.ipynb

NOTA: las imágenes de Docker de jupyter son realmente grandes (1GB). Descargar con buena conexión, por favor no utilizar la conexión de la facultad para descargar en clase.
