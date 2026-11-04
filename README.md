# Cuaderno de Música de las Matemáticas

Edición digital comparada de un cuaderno manuscrito de 151 páginas. Cada página muestra el escaneo a la izquierda y su transcripción a la derecha, en marcos del mismo tamaño.

La transcripción usa bloques `<pre class='pag'>` para conservar aproximadamente los saltos de línea, las sangrías y la disposición del texto. Cada página ocupa una cuadrícula de 60 filas. Los dibujos y trazos del manuscrito se consultan en la imagen original.

## Cómo abrirlo

Descarga o clona el repositorio y abre `index.html` en un navegador. Mantén las carpetas junto al HTML. No requiere instalación ni servidor.

En pantallas pequeñas, desplázate horizontalmente para ver la pareja completa. La fuente Red Hat Mono se carga desde Google Fonts; sin conexión se usa una fuente monoespaciada disponible en el equipo.

## Archivos

- `index.html`: las 151 parejas de imagen y transcripción.
- `assets/img/`: imágenes JPG numeradas por página.
- `transcripciones/`: un archivo TXT UTF-8 por página.
- `assets/css/estilos.css`: estilos y tipografía.
- `assets/js/lectura.js`: ajuste de escala de las transcripciones.
- `favicon.svg` y `favicon.png`: icono del sitio.

Para editar una transcripción, actualiza su TXT y el bloque correspondiente en `index.html`, conservando los espacios y las 60 filas.
