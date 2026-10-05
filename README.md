# Dataset de defectos en café verde

Estructura inicial para imágenes y sus anotaciones:

```text
train/
  images/   # imágenes de entrenamiento
  labels/   # anotaciones correspondientes
val/
  images/   # imágenes de validación
  labels/   # anotaciones correspondientes
test/
  images/   # imágenes de prueba
  labels/   # anotaciones correspondientes
```

Mantén el mismo nombre base para cada imagen y su anotación (por ejemplo,
`lote_001.jpg` y `lote_001.txt`). Deja las imágenes y anotaciones de cada
muestra en el mismo split. El formato de las anotaciones y las clases de
defectos quedan por definir según la tarea o herramienta de análisis que se
utilice.
