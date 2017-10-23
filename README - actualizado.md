# AppLove

Para completar la web **AppLove** he utilizado diferentes recursos de este repositorio boilerplate (plantilla inicial) el que incluía imágenes y algunas clases CSS ya creadas que servirían de ayuda para este proyecto. 

## Empezar por realizar un fork y clonar este repositorio.

1. Una vez realizado este proceso abrir la carpeta en editor de preferencia (en mi caso SUBLIME).

2. Posteriormente utilizando como base el **archivo HTML** de este repositorio boilerplate, se procede a agregar clases y etiquetas que se estimen convenientes (para mi fueron de utilidad agregar < ul > y < li > para ordenar ciertas secciones).

    1. Comenzar por agregar y nombrar clases a etiquetas section o div para poder modificarlas en el archivo css de manera más fácil.
    2. Agregar las imágenes que se encuentran dentro de la carpeta **assets**.
    3. Asegurarse de no repetir nombres para no generar confusión o dificultades al momento de hacer cambios más adelante.
    4. Asegurarse de cerrar bien cada etiqueta para evitar problemas.

3. Luego proseguimos con CSS. Este archivo contiene ciertos estilos, para la tipografía y colores y así ayudar a la maquetación exacta de la web **AppLove**. 

4. En esta parte se comenzó a componer la estructura visual del documento:

    1. Llamando a las **clases** que se nombraron en el **archivo HTML**.
    2. Otorgándoles valor a cada una en cuanto a color de las **fuentes**, **tamaño**, **alineación** o estilo específico, como por ejemplo:
    
    ```CSS
    .text-uppercase {
      text-transform: uppercase;
    }
    ```
    3. También se **flotaron** algunos elementos para facilitar sus deplazamiento dentro de la página.
    4. Y se modificaron las propiedades de las **imágenes**.

## Objetivo Final

Todo esto para maquetar la web **AppLove**, esperando llegar al siguiente resultado:

![AppLove](https://fotos.subefotos.com/1edc0aab51f1d624da4a24ab86129d87o.png) 

## Detalles adicionales

- En la carpeta `css` existe un archivo base `main.css` donde hay clases reutilizables, las cuales pueden ser usadas más de una vez.

- El `header` tiene que estar **estático**, como se muestra en la siguiente _imagen gif_:

![AppLove-gif](https://fotos.subefotos.com/da068e44cb72b36ba6c4458130c00185o.gif) 

- Dentro de la carpeta `assets` se encuentra la carpeta `images` donde se encuentran todas las imágenes necesarias para el proyecto.

