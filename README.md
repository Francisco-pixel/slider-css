# slider-css

### Descripción
Este slider utiliza etiquetas HTML y estilos CSS para crear un diseño simple de slider. Aquí hay algunas claves para entender el código:

### HTML5

```HTML
<div class="contenedor-slider">: Contenedor principal del slider.
<div class="sliders" style="--sliderMax:3;">: Contenedor de las diapositivas (sliders).
<div class="slider">: Cada diapositiva individual con una imagen y un párrafo de descripción.
<div class="btns">: Botones de radio para cambiar entre diapositivas.
```

### CSS3
```CSS
:root: Define variables de color y transición.
.contenedor-slider: Estiliza el contenedor principal del slider.
.sliders: Contenedor de diapositivas con flexibilidad y ancho dinámico.
.slider: Estilos básicos para cada diapositiva.
.slider__img: Estilos para la imagen dentro de cada diapositiva.
.desc: Estilos para la descripción en la esquina inferior derecha de cada diapositiva.
.btns: Estilos para el contenedor de botones de radio.
.check: Estilos para los botones de radio.
:has(.check:checked:nth-of-type(n)) .slider:nth-of-type(n): Usa el selector :has para aplicar estilos a la diapositiva seleccionada.
```

### Personalización

>Puedes personalizar este slider ajustando las imágenes, colores, y dimensiones en el archivo HTML y CSS según tus necesidades. Experimenta con las variables y propiedades para lograr el diseño deseado.