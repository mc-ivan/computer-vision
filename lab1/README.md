# Laboratorio 1 - Conteo de Objetos mediante Visión Clásica

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/mc-ivan/computer-vision/blob/main/lab1/notebook/Practica1_Grupo3.ipynb)

## Grupo 3

| Integrante |
|------------|
| Ivan Mamani|
| Yesica Luna |
| Elvis Miranda |
| Karem Huacota |
| Karen Torrico |

Este laboratorio implementa el **conteo de objetos en movimiento usando visión computacional clásica**, sin utilizar Deep Learning.  
Se enfoca en la **detección y conteo de atletas cruzando la línea de meta** y **vacas cruzando un río**, usando técnicas de procesamiento de imágenes y análisis de contornos.


## Objetivos

1. Aprender a procesar videos con OpenCV y NumPy.  
2. Detectar objetos en movimiento mediante técnicas clásicas de visión computacional.  
3. Implementar conteo automático de objetos que cruzan una línea de interés.  
4. Visualizar resultados en video y capturas de imagen.


## Contenido del repositorio

- `lab1/sources/` : Videos y capturas del laboratorio  
- `lab1/notebook/` : Notebook e informe de laboratorio con análisis y resultados  
- `Colab` : [Abrir en Google Colab](https://colab.research.google.com/tu-link-al-colab)


## Videos y resultados

### 1. Cruce de línea de meta de atletas

| Tipo | Archivo | Tamaño |
|------|--------|--------|
| Video original | [atletas.mp4](/lab1/sources/atletas.mp4) | 49 MB |
| Video procesado | [atletas-conteo_compressed.mp4](/lab1/sources/atletas-conteo_compressed.mp4) | 36 MB |
| Imagen ejemplo | ![Conteo de atletas](/lab1/sources/conteo_atletas.png) | 2.5 MB |

### 2. Cruce de río de vacas

| Tipo | Archivo | Tamaño |
|------|--------|--------|
| Video original | [vacas.mp4](/lab1/sources/vacas.mp4) | 52 MB |
| Video procesado | [vacas-conteo-compressed.mp4](/lab1/sources/vacas-conteo-compressed.mp4) | 82 MB |
| Imagen ejemplo | ![Conteo de vacas](/lab1/sources/conteo_vacas.png) | 5.2 MB |

> Haz clic en los links para ver los videos completos.  


## Resumen de casos

| Caso | Descripción | Video Original | Video Final |
|------|------------|----------------|-------------|
| Cruce de línea de meta | Conteo automático de atletas cruzando la meta | [Original](/lab1/sources/atletas.mp4) | [Final](/lab1/sources/atletas-conteo_compressed.mp4) |
| Cruce de río | Conteo automático de vacas cruzando un río | [Original](/lab1/sources/vacas.mp4) | [Final](/lab1/sources/vacas-conteo-compressed.mp4) |


## Notebook del laboratorio

- El notebook contiene:  
  - Lectura de videos y frames.  
  - Procesamiento de imagen (detección de contornos y movimiento).  
  - Implementación del conteo automático.  
  - Visualización de resultados.  

**Notebook**: [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/mc-ivan/computer-vision/blob/main/lab1/notebook/Practica1_Grupo3.ipynb)


**Informe de Laboratorio:** `/lab1/notebook/Laboratorio1-Informe-Grupo3.pdf`
