# Fundamentos Web: HTML5 y CSS3

Enunciado de la práctica Full Stack Web Bootcamp XI Edición ([versión en PDF](./docs/000-Enunciado-Practica-HTML5-CSS3-WEB11.pdf))

**INFORMACIÓN DE CONTACTO DEL INSTRUCTOR**

    Tony G. Bolaño
    tony@tonygb.com
    https://www.linkedin.com/in/tonybolanyo/

## Creación de un sitio web para plataforma online de contenido digital.

### Consideraciones generales

- No se permite el uso de librerías y frameworks externos como Bootstrap, Spectre.css o similares.
- Se deberá crear una o más hojas de estilo CSS para aplicar el diseño deseado a la web.
- La página web debe visualizarse correctamente en las versiones actuales de Google Chrome, Mozilla Firefox y Microsoft Edge.
- No se requiere el uso de interacción mediante JavaScript.

### Descripción de la práctica

Nuestro objetivo es construir la estructura web de una plataforma de streaming de contenido digital al estilo de Netflix o HBO para distribuir series y películas a cualquier dispositivo conectado a internet que disponga de un navegador web moderno. Nuestro público es de diferentes edades y condiciones y queremos que dispongan de la mejor experiencia de usuario independientemente del tamaño de su pantalla.

Como estamos buscando un producto mínimo viable que podamos poner en marcha enseguida nos centraremos solamente en tres pantallas o secciones:

1. Al llegar a la plataforma se debe mostrar un formulario de login para acceder al contenido. En este formulario se debe implementar:

   a. Un campo para el email, que servirá como nombre de usuario

   b. Un campo para la contraseña

   c. Un botón para realizar el login y acceder al contenido

   d. Un enlace para iniciar el proceso de recordar una contraseña olvidada

2. La pantalla principal del contenido que contendrá, al menos, los siguientes elementos:

   a. Un menú superior, que debe incluir el logotipo de la plataforma, opciones para acceder a la sección de novedades, series, películas o favoritos, un formulario de búsqueda y la opción para cerrar la sesión.

   b. Una “rejilla” de películas o series de forma que en cada elemento se muestre una miniatura de la serie/película/episodio. Además, al situar el ratón encima, se mostrará sobre la miniatura información adicional: título, calificación, año de publicación y sinopsis resumida.

   c. Cada película o serie contendrá un icono que permitirá marcarla como favorita. Si el contenido está marcado como favorito, el icono se mostrará de forma diferente de manera que se distinga fácilmente el contenido favorito del resto.

   d. (OPCIONAL) Un carrusel de gran tamaño con el contenido destacado.

3. Una ficha detalle de la película/serie/episodio. Debe contener al menos:

   a. El mismo menú superior de la pantalla principal

   b. Información básica de la película/serie/episodio: título, calificación, año de publicación, sinopsis completa y listado de actores.

   c. Carátula o trailer. El trailer debe poder reproducirse en la propia página. En caso de tratarse de un vídeo no se acepta la inclusión mediante marcos iframe.

   d. “Rejilla” con contenido relacionado, que se usará para los episodios en el caso de una serie o para películas similares en el caso de las películas.

4. (OPCIONAL) Crear una página de error 404 Not Found. Esta página es de implementación opcional. La página debe contener de forma destacada el código y el título del error (404, Página no encontrada). Para evitar que el visitante abandone la página, incluirá (al menos) una de estas dos opciones: un enlace para volver al inicio, un mapa del contenido del sitio web.

5. (OPCIONAL) Una página de Coming Soon que incluya un contador de días, horas, minutos y segundos, la fecha de lanzamiento y un formulario para suscribirse a las novedades.

### Detalles de implementación

- La estructura de la web tendrá en cuenta las etiquetas de contenido semántico.
- Debéis incluir las media queries necesarias para que el diseño sea responsivo.
- Las animaciones o interactividad propuesta deben realizarse exclusivamente mediante técnicas CSS sin el uso de librerías externas.
- No es necesario realizar múltiples páginas distintas para diferentes películas. Cualquier película, serie o episodio enlazará con la misma página de detalle.
- Se valorará el uso de atributos especiales de accesibilidad, microformatos…
- Los apartados marcados como opcionales no son necesarios para obtener la calificación de APTA, pero se valorarán positivamente.

## Recursos

- [Apuntes HTML5](./docs/001-HTML5.pdf)

- Shortcuts para VS Code

  - [Linux](./docs/100-VSCode-shortcuts-linux.pdf)
  - [Windows](./docs/100-VSCode-shortcuts-windows.pdf)
  - [Mac](./docs/100-VSCode-shortcuts-mac.pdf)

- [Resumen de etiquetas HTML5](./docs/101-resumen-etiquetas-HTML5)
