# Que es SVG?

### Scalable Vector Graphics

Los archivos de gráficos vectoriales escalables (SVG) son un tipo de formato de imagen, similar a los archivos de marcado HTML que permiten crear gráficos basado en vectores.

hay 3 formas diferentes de utilizar imágenes SVG en nuestras páginas. Desde ficheros **SVG externos**, desde **SVG en línea** y desde **Data URI**.

## La etiqueta SVG

### Elemento SVG

La etiqueta `svg` es el **elemento padre** de cualquier imagen vectorial SVG que estemos creando, ya que todos los elementos deben estar en su interior. Es el equivalente a la etiqueta `html` respecto al lenguaje HTML.

**Namespace (atributo `xmlns`)**:  El atributo xmlns procede de xml namespace y permite indicar una URL donde se encuentra información sobre la especificación que se va a utilizar de SVG.

**El atributo `preserveAspectRatio`**: se usa para determinar como se mantendrá la proporción de aspecto de un lienzo de SVG con un `viewBox` definido.

# Rectángulos y cuadrados

### El elemento SVG `rect`


# Círculos

### El elemento `circle`

La etiqueta `circle` nos permite crear círculos en nuestro archivo SVG. La etiqueta tiene varios atributos que permiten establecer su radio o las coordenadas de posición. A diferencia del rectángulo, lo que se posiciona es el centro del círculo, mediante los atributos cx (en horizontal) y cy (en vertical).
