# Sistema de optimización de consumo hídrico en las viviendas

En este repositorio se ha implementado un sistema que permite descomponer una serie de consumo de agua en una vivienda en eventos, centrándose en los siguientes:

- WC
- Llenado de bañera
- Ducha
- Grifo
- Lavadora
- Lavavajillas

Cada uno tendrá unas características propias, lo cual se utilizará para su identificación en la serie.

El objetivo es lograr identificar los eventos y clasificarlos según su tipo, para lo que se propondrán algoritmos de clustering que agrupen los eventos identificados para posteriormente etiquetarlos.

## Estructura

- data/ : Directorio donde se guardarán los archivos referentes a datos persistentes.
- data/datasets/ : Directorio donde se pueden encontrar los datasets generados durante el desarrollo del sistema para reducir el tiempo de computación.
- data/simulaciones/ : Directorio en el que se guardarán los archivos correspondientes a las series simuladas.
- TFM.ipynb : Cuaderno Jupyter donde se implementará todo el sistema.

