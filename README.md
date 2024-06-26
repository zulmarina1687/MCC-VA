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
  - Convolución
  - Template Matching
 
### 1. Modificar el brillo y contraste - Gamma Correction
- Para verificar el código ir a este [Link Colab](/Lab1_Gamma.ipynb)

Entrada:
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/image.jpg" width="312" height="495" >
</div>

Salida: 0.6 - GPU 
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/image_gamma_gpu.jpg" width="312" height="495">
</div>
Salida: 0.6 - Python                                                                  
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/image_gamma_python2.jpg" width="312" height="495">
</div>
  
### 2. Ecualización de una imagen
- Para verificar el código ir a este [Link Colab](/Lab1_Equalized.ipynb)

Entrada:
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/img.jpg" width="540" height="325">
</div>

Salida con GPU:  
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/img_equalized_gpu.jpg" width="540" height="325">
</div>

Salida con Python:  
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/img_equalized_python.jpg" width="540" height="325">
</div>

### 3. Operación Aritmética (Ejm: Suma y Resta de imágenes)
- Para verificar el código ir a este [Link Colab](/Lab1_AddSubImage.ipynb)

Entrada:
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/leon.jpg" width="680" height="400">
</div>
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/plaza.jpg" width="680" height="400">
</div>

Salida con GPU: Suma de imágenes 
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/plaza_add_gpu2.jpg" width="680" height="400">
</div>

Salida con GPU: Resta de imágenes 
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/plaza_sub_gpu.jpg" width="680" height="400">
</div>

Salida con Python: Suma de imágenes 
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/plazaR_add.jpg" width="680" height="400">
</div>
Salida con Python: Resta de imágenes 
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/plazaR_sub.jpg" width="680" height="400">
</div>

### 4. Convolucion
- Para verificar el código ir a este [Link Colab](/Lab1_Convolution.ipynb)

Entrada:
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/pikachu.jpg" width="300" height="300">
</div>

Salida con GPU:
- Sobel
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/pikachu_Sobelx_gpu.jpg" width="300" height="300">
</div>
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/pikachu_Sobely_gpu.jpg" width="300" height="300">
</div>
- Perfilado
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/pikachu_Perfilado_gpu.jpg" width="300" height="300">
</div>
- Filtro Gaussiano
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/pikachu_FiltroGaussiano_gpu.jpg" width="300" height="300">
</div>

### 4. Template Matching
- Para verificar el código ir a este [Link Colab](/Lab2_TemplateMatching.ipynb)

Entrada:
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/fotogrupal.jpg" width="1024" height="683">
</div>
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/face.jpg">
</div>

Salida GPU:
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/fotogrupal_gray_gpu.jpg" width="1024" height="683">
</div>
<div>
  <img src="https://github.com/zulmarina1687/MCC-VA/blob/main/Resultados/fotogrupal_color_gpu.jpg" width="1024" height="683">
</div>

