# html 
lenguaje de marcado de texto, es la parte que nos permite estructurar nuestra página web, es como el esqueleto de nuestra aplicación.
Su principal objetivo es darle formato semántico a nuestra información a través del uso de 'elementos', que a su vez están conformados por 'etiquetas' de apertura y cierre, y un 'contenido'.

- [!TIP] en algunos casos encontraremos los "elementos" huérfanos, estos solo están conformados por una sola "etiqueta".

## estructura de un elemento en html

## estructura fundamental del documento de html 
- `<!DOCTYPE html>` - declaramos el tipo de documento, este huérfano indica al navegador que el documento con el que se está trabajando y que deberá realizar es 'html', **siempre debe estar en la primera línea**.
- `<html></html>` - elemento raíz que envuelve todo el contenido de la página html, este elemento tiene dos hijos principales.
- `<head></head>` - elemento de configuración, contiene información importante sobre el documento como (título, enlaces css, información para motores de busqueda, descripción entre otros).
- `<title></title>` - elemento de título de página, es el hijo de 'head' y define el título que aparecerá en la pestaña del navegador.
- `<body></body>` - elemento del cuerpo del documento, contiene toda la parte visual y los elementos públicos que el usuario final podrá ver e interactuar en la página web.

## estructura de contenido semántico (secciones principales)

- `<header></header>` - Elemento que define la cabecera de la página o de una sección, suele contener el logotipo, títulos y el menú de navegación.
- `<nav></nav>` - Elemento de navegación, se utiliza específicamente para contener bloques de enlaces o menús principales del sitio.
- `<main></main>` - Elemento del contenido principal, contiene el bloque de información único y central de la página (solo debe haber uno por documento).
- `<section></section>` - Elemento que representa una sección genérica y temática del contenido, se usa para agrupar temas relacionados.
- `<article></article>` - Elemento que representa un contenido autónomo e independiente que tiene sentido por sí mismo (como un post de blog o noticia).
- `<aside></aside>` - Elemento para contenido secundario o tangencial, ideal para barras laterales, publicidad o notas relacionadas.
- `<footer></footer>` - Elemento del pie de página, contiene información de derechos de autor (copyright), enlaces legales, redes sociales o contacto.