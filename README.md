# VC_P2_Pedro_Batista_Sosa
# Procesamiento de Imágenes con OpenCV - Tareas Realizadas

## Introducción

Este proyecto ha sido desarrollado utilizando el entorno de la practica 1, para ello creamos y ejecutamos el entorno en **Anaconda** tal y como se especifica en la práctica 1, este contiene los paquetes necesarios para el procesamiento de imágenes con **OpenCV**, **NumPy** y **Matplotlib**. Para ejecutar las tareas, es necesario activar este entorno previamente.

### Activar el entorno `ENV_VC`:

1. Abrir una terminal o el **Anaconda Prompt**.
2. Ejecutar el siguiente comando para activar el entorno:

   ```bash
   conda activate ENV_VC
   ```

Una vez activado, estarás listo para ejecutar los scripts de las tareas descritas a continuación.

## Índice

1. [Tarea 1 Cuenta de Píxeles Blancos por Filas](#Tarea-1-Cuenta-de-Píxeles-Blancos-por-Filas)
2. [Tarea 2 Umbralizado y Conteo de Píxeles Sobel vs. Canny](#Tarea-2-Umbralizado-y-Conteo-de-Píxeles-Sobel-vs-Canny)
3. [Tarea 3 Demostrador con Cámara y Funciones de OpenCV](#Tarea-3-Demostrador-con-Cámara-y-Funciones-de-OpenCV)
4. [Tarea 4 Demostrador Inspirado en Vídeos](#Tarea-4-Demostrador-Inspirado-en-Vídeos)

## Tarea 1 Cuenta de Píxeles Blancos por Filas

### Descripción
Realiza la cuenta de píxeles blancos por filas (en lugar de por columnas). Determina el valor máximo de píxeles blancos para filas, maxfil, mostrando el número de filas y sus respectivas posiciones, con un número de píxeles blancos mayor o igual que 0.95*maxfil.

## Tarea 2 Umbralizado y Conteo de Píxeles Sobel vs Canny

### Descripción
Aplica umbralizado a la imagen resultante de Sobel (convertida a 8 bits), y posteriormente realiza el conteo por filas y columnas similar al realizado en el ejemplo con la salida de Canny de píxeles no nulos. Calcula el valor máximo de la cuenta por filas y columnas, y determina las filas y columnas por encima del 0.95*máximo. Remarca con alguna primitiva gráfica dichas filas y columnas sobre la imagen. ¿Cómo se comparan los resultados obtenidos a partir de Sobel y Canny?

## Tarea 3 Demostrador con Cámara y Funciones de OpenCV

### Descripción
Proponer un demostrador que capture las imágenes de la cámara, y les permita exhibir lo aprendido en estas dos prácticas ante quienes no cursen la asignatura :). Es por ello que además de poder mostrar la imagen original de la webcam, incluya al menos dos usos diferentes de aplicar las funciones de OpenCV trabajadas hasta ahora.

## Tarea 4 Demostrador Inspirado en Vídeos

### Descripción
Tras ver los vídeos [My little piece of privacy](https://www.niklasroy.com/project/88/my-little-piece-of-privacy), [Messa di voce](https://youtu.be/GfoqiyB1ndE?feature=shared) y [Virtual air guitar](https://youtu.be/FIAmyoEpV5c?feature=shared) proponer un demostrador reinterpretando la parte de procesamiento de la imagen, tomando como punto de partida alguna de dichas instalaciones.
