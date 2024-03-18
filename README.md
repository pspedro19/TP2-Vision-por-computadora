# Análisis de Imágenes TP2

Pedro Perez 
Barbara Cocco

Este proyecto contiene un conjunto de notebooks de Google Colab que demuestran diferentes técnicas de procesamiento y análisis de imágenes utilizando OpenCV y Python.

## Contenido

- `TP1.ipynb`: 
Implementar la función
create_gauss_filter (h, w, k_size , para crear filtros gaussianos para
filtrado espectral. Debe retornar un filtro gaussiano de tamaño HxW en dominio espacial y su transformada
de Fourier.
1.
Graficar ambas representaciones para diferentes tamaños de
kernel y sigma. Aplicar el filtro una
imagen para validar el funcionamiento en el dominio espectral.
2.
Usando el método descripto en el
paper Image Sharpness Measure for Blurred Images in Frequency
Domain” comparar el resultado de un filtrado por convolución con el filtrado espectral
3.
Repetir
la comparación usando uno de los métodos descriptos en el apéndice del paper “Analysis of
focus measure operators in shape from focus”
## Requisitos

Para ejecutar estos notebooks, necesitarás:

- Python 3.x
- [OpenCV](https://opencv.org/) para el procesamiento de imágenes
- [NumPy](https://numpy.org/) para cálculos numéricos
- [Matplotlib](https://matplotlib.org/) para la visualización de imágenes

Puedes instalar todas las dependencias necesarias utilizando el siguiente comando:

```bash
pip install numpy opencv-python matplotlib
```
## Requisitos

Para utilizar estos notebooks, simplemente clona este repositorio y abre los archivos .ipynb con Google Colab o Jupyter Notebook.

```bash
git clone https://github.com/pspedro19/TP2-Vision-por-computadora.git

```
