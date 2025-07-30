# Redes en la Cámara de Diputadas y Diputados de Chile

El presente repositorio contiene el proceso de creación para la siguiente
visualización, que muestra las redes formadas en la Cámara de Diputadas y
Diputados de Chile según qué tan parecido vota cada par de diputados.

![Red de similitud entre miembros de la Cámara de Diputadas y Diputados de
Chile](img/red.png)

Se observa la formación de seis comunidades con distintas relaciones entre sí.
Estas comunidades corresponden principalmente a bloques políticos establecidos,
aunque igualmente se presentan resultados interesantes (p.ej. la división de
diputados del Frente Amplio y la UDI en más de una comunidad, contrario al
resto de partidos políticos establecidos).

El proceso de extracción de datos se presenta en el *notebook*
[`data_extraction.ipynb`](data_extraction.ipynb), mientras que la creación de
la visualización como tal se presenta en el *notebook*
[`visualization.ipynb`](visualization.ipynb). Para este último se utilizó el
repositorio [aves](https://github.com/zorzalerrante/aves), por Eduardo
Graells-Garrido y Daniela Optiz.