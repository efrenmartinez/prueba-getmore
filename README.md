# Prueba de Maquetación de Homepage (Desktop y Móvil) para @getmore

### NOTAS PARA LA PRUEBA

Está Permitido:
  - Utilizar frameworks y librerías Javascript (Angular, Rect, Vue, etc).
  - Utilizar procesadores CSS o también CSS puro.

NO está permitido:
  - El uso de frameworks CSS o cualquier tipo de librería de estilos predefinidos.

## SOLUCIÓN

El proyecto lo realice con:
  * HTML puro.
  * SASS.
  * JavaScript Vanilla (JavaScript Puro).

Las herramientas que usé fueron:
  * **live-server** para correr un servidor desde mi maquina.
  * **node-sass** para poder escribir SCSS y ahí compilarlo a un archivo CSS (main.css).
  * **VERCEL** para hacer el deploy.

Tomé la desición de solo usar esas tecnologías por que solamente era una homepage sencilla sin nada de lógica, ni otras páginas.

El proyecto esta dividido en diferentes carpetas y archivos, las cuales son
  * Carpeta assets -- Carpeta para las imágenes y la fuente de la pagina.
  * Carpeta css -- Carpeta donde se encuentra el archivo CSS compilado de SASS.
  * Carpeta js -- Carpeta para un archivo JS que le da funcionalidad al carousel.
  * Carpeta scss -- Está carpeta de encuentra dividido en diferentes carpetas y archivos:
    * Carpeta abstracts -- Donde declaro las variables de SASS. Para definir los colores.
    * Carpeta base
      * general -- Estilos generales de la página.
      * reset -- Estilos para resetear los valores predefinidos del navegador.
      * typography -- Estilos para la tipografia
    * Carpeta components -- Estilos para botones, carousel, sliders, footer y demás sections de la página.
    * Archivo main.scss -- Archivo que uso para hacer los imports de los demás archivos SCSS.
  * Archivo index.html

### Dificultades.

Las dificultades que me enfrente fue la realización del carousel y el slider, ya que siempre he usado framework de CSS que te ayudan con esos componentes, pero me agrado poder realizarlos.
