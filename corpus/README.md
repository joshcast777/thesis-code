# Proceso de creación del corpus

Estos son scripts en Python utilizados para la creación del corpus.

## Información de la Tesis

La tesis contempla el análisis de si las definiciones, ejemplos y casos de uso generados por GPT-3 son útiles para la síntesis de textos científicos.

## Función del Proyecto en la Tesis

Estos scripts se ejecutaron para obtener el resultado final del corpus, obtenidos de otros archivos de Excel obtenidos del evento Simpletext@CLEF-2023.

## Herramientas utilizadas

Los scripts fueron hechos con Python ejecutado en Google Colab.

## Instalación y ejecución

Se deben realizar las ejecuciones en Google Colab.

Primero, se debe crear una carpeta `data/`, y en esta agregar los siguietes archivos:

Para la ejecución de fs_zs_joined.ipynb:

* PRM_FS_TASK2_2_V1.xlsx
* PRM_ZS_TASK2_2_V1.xlsx

Para la ejecución de first_population.ipynb:

* simpletext-task2-test-large.xlsx
* simpletext-task2-test-medium.xlsx
* simpletext-task2-test-small.xlsx

Estos archivos también se encuentran en la carpeta `data\` en el proyecto.

Finalmente, se deben ejecutar los scripts en el siguiente orden:

1. fs_zs_joined.ipynb
2. first_population.ipynb
3. separate_fields.ipynb
4. add_sample.ipynb

Los resultados se guardarán en la misma carpeta `data\` y serán necesarios para la siguiente ejecución. Entonces, lo que devuelva la ejecución, se lo deberá pasar a la carpeta `data\` de la siguiente ejecución.
