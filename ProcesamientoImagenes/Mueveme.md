Tags: [[Procesamiento de Imágenes]]

---
# Procesos de la aplicación de máscaras
### Convolución:
La **convolución** es el proceso por el cual una máscara se aplica a una imagen, operando cada píxel y sus vecinos para generar un nuevo valor para el píxel central. La formula general para la convolución es:
_Recuerda añadir la formula_

### Correlación:
La **correlación** es muy similar a la convolución, pero sin invertir el kernel, A menudo, en la práctica, se usa una convolución porque en muchos filtros, invertir el kernel no afecta el resulta.

## Aplicaciones Comunes:
# Filtros
## Filtro promedio:
Este filtro es un filtro de suavizado que reemplaza cada píxel en la imagen con el promedio de píxeles de su vecindario. El filtro promedio es útil para **reducir el ruido** en las imágenes, pero también puede hacer que la imagen se vea borrosa.

### Máscara de filtro Promedio
_Inserta matriz de 3 x 3_

## Filtro mediano:
El filtro mediano es otro filtro de suavizado, pero en lugar de calcular el promedio de los píxeles vecinos, selecciona el valor mediano. Este filtro es eficaz para eliminar el ruido impulsivo, preservando mejor los bordes en comparación con el filtro promedio.

## Filtro Laplaciano
El **filtro laplaciano** es un filtro de detección de bordes basado en el operador Laplaciano, que calcula la segunda derivada de la imagen. Esto hace que sea muy sensible a los cambios bruscos en la intensidad de los píxeles, lo que permite detectar bordes.

### Máscara
[[0,1,0], [1,-4, 1], [0,1,0]]


