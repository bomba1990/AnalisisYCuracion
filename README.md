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

NOTA: las imágenes de Docker de jupyter son realmente grandes (1GB). Descargar con buena conexión, por favor no utilizar la conexión de la facultad para descargar en clase.
