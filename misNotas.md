# Notas Clase HTML

`<title>Document</title>` Muestra el título que sale en la pestaña de la página y que usará el buscador.

Para usar el browsersync, ir a la carpeta que contiene la web que nos interesa (en este caso es dia-1), botón der ratón --> *BrowserSync start*

**f12** para entrar en inspector de código en cualquier página web.

En la cabecera (header) espero encontrar el logotipo...

En *main* tiene que estar el contenido de verdad de la pgina. IMP!!. Todo el texto.

`<div>` no tiene estructura semántica

Para hacer un párrafo 5 veces y cnon contenido aleatorio:
`p*5>lorem`

Link con ruta relativa: <a href="/index.html">Of course!</a>
porque empieza con la barra.
Una ruta absoluta e,pieza con http://...bla bla

No es buena idea poner teléfonos o email en frontend escrito tal cuel en html pq los buscarán para spam.

target le indica al enlace donde tiene q abrir. El destino.
rel tienen palabras claves q t dice el tipo de relacion con la pagina web a la que hace referencia el enlace.
- no follow, le dice a los motores de búsquedas no sigas
- noopener ... ?¿

atajo para mover todo el bloque deleccinado en html: seleccionas el párrafo y apretas ALT + la flecha del teclado.


Si un link (a) le pongo un target "marco" abrirá enl link en un iframe con id=marco y name=marco, de esta manera abres una segunda pagina dentro del frame sin salir de la pestaña.

Tablas: mejor trabajar con <thead>, <tbody> y <tfoot>