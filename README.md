# Semana Tec - Camara Inteligente -

## Instalar dependencias necesarias

Después de clonar este repositorio, es necesario instalar:

- Python3
- OpenCV
- Numpy

## Aplicaciones

El archivo main está compuesto por un condicional que, dependiendo de la entrada del usuario, correrá el filtro indicado, dichos filtros se pueden correr por separado en los siguientes archivos y se explican brevemente:

- filtro1.py: Este filtro abre la cámara y no coloca ningún filtro. 
- Filtro2.py: Este filtro invierte los colores de la imagen.
- filtro3.py: Este filtro difumina la imagen.
- filtro4.py: Este filtro gira 180° la imagen, se podría decir que te pone de cabeza.
- filtro5.py: Este filtro hace que solo se vea en la imagen cualquier objeto azul y el fondo negro.
- filtro6.py: Este filtro convierte la imagen a escala de grises.
- filtro7.py: Este filtro hace un efecto de acuarela a la imagen.
- Filtro8.py: Este filtro nos da una imagen como visión térmica

## Usage

Para poder ejectutar los codigos se deben imoprtar las siguientes librerías.
- cv2: esta librería es clave ya que fue diseñada para "computer vision".
- time: utilizada para mostrar al usuario por cuánto tiempo fue corrido el código.
- argparse: que facilita la escritura de interfaces de línea de comandos, en este código nos ayuda a abrir la cámara.
- numpy: en ciertos filtros se utilizan arreglos de numpy para facilitar el manejo de los pixeles.
- matplotlib: utilizada en el filtro 8 por su paleta de colores cálidos.
