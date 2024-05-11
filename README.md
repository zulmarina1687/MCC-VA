# Maestría en Ciencia de la Computación - Visión Artificial
## Integrantes
- Gomez Contreras, Junior Valentin
- Pilco Pancca, Luz Marina
- Sejje Condori, Erika

## Algoritmos
- Implementar en GPU las siguientes operaciones.
  - Modificar el brillo y contraste - Gamma Correction
  - Ecualización de una imagen
  - Operación Aritmética (Ejm: Suma de imágenes)
  - Convolucion
  - 
 
### 1. Modificar el brillo y contraste - Gamma Correction
- Para ejecutar ir a este [Link]([https://colab.research.google.com/drive/175jk0dhvUKP6SX6UNTuzkKR1zUwScu5_#scrollTo=gA6KhQZEFoxl](https://github.com/zulmarina1687/MCC-VA/blob/main/Lab1_Gamma.ipynb))

Entrada:
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/image.jpg" width="512" height="695" >
</div>

Salida: 0.6 - GPU 
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/image_gamma_gpu.jpg" width="512" height="695">
</div>
Salida: 0.6 - Python                                                                  
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/image_gamma_python2.jpg" width="512" height="695">
</div>
  
### 2. Ecualización de una imagen
Entrada:
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/img.jpg">
</div>

Salida con GPU:  
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/img_equalized_gpu.jpg">
</div>

Salida con Python:  
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/img_equalized_python.jpg">
</div>

### 3. Operación Aritmética (Ejm: Suma de imágenes)
Entrada:
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/leon.jpg" width="780" height="500">
</div>
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/plaza.jpg" width="780" height="500">
</div>

Salida con GPU: Suma de imágenes 
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/plaza_add_gpu2.jpg" width="780" height="500">
</div>

Salida con GPU: Resta de imágenes 
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/plaza_sub_gpu.jpg" width="780" height="500">
</div>

Salida con Python: Suma de imágenes 
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/plazaR_add.jpg" width="780" height="540">
</div>
Salida con Python: Resta de imágenes 
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/plazaR_sub.jpg" width="780" height="500">
</div>

### 4. Convolucion
Entrada:
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/tigre.jpg" width="567" height="369">
</div>

Salida con GPU:
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/tigre_conv_gpu.jpg" width="567" height="369">
</div>
