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



Estructura de texto
jerarquia de encabezados
descripcion
ejemplo
<!--el html de ejemplo-->

parrafos y enfasis
listas
citas y referencias
codigo y texto tecnico
lineas y saltos
#### ejemplo practico que contenga todo anterios
en carpeta raiz crearan una carpeta de nombre ejercicio_01 dentro de la carpeta crearan el archivo index.html dentro de este archivo aran el ejemplo practico integrador (que tendra todas etiquetas trabajas hasta el momento).
como titulo del ejemplo integrador tendran que desasaroollar un receta de cocina.



# 📝 Estructura de texto

La estructura de texto en HTML sirve para organizar el contenido de una página web de forma clara y ordenada.  
Permite agregar títulos, párrafos, listas y otros elementos importantes.

---

# 🔠 Jerarquía de encabezados

Los encabezados sirven para crear títulos y subtítulos según su importancia.

| Etiqueta | Función |
|----------|----------|
| `<h1>` | Título principal |
| `<h2>` | Subtítulo |
| `<h3>` | Subtema |
| `<h4>` | Encabezado secundario |
| `<h5>` | Nivel menor |
| `<h6>` | Último nivel |

## 💻 Ejemplo

```html
<h1>Título principal</h1>
<h2>Subtítulo</h2>
<h3>Subtema</h3>
```

---

# 📄 Párrafos y énfasis

Los párrafos sirven para escribir información o descripciones dentro de la página web.

El énfasis sirve para resaltar palabras importantes.

| Etiqueta | Función |
|----------|----------|
| `<p>` | Crear párrafos |
| `<strong>` | Texto importante en negrita |
| `<em>` | Texto con énfasis en cursiva |

## 💻 Ejemplo

```html
<p>Este es un párrafo.</p>

<p>
Texto con <strong>importancia</strong>
y texto con <em>énfasis</em>.
</p>
```

---

# 📋 Listas

Las listas sirven para organizar información de manera ordenada o desordenada.

| Etiqueta | Función |
|----------|----------|
| `<ul>` | Lista desordenada |
| `<ol>` | Lista ordenada |
| `<li>` | Elemento de lista |

## 💻 Ejemplo

```html
<ul>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
</ul>

<ol>
    <li>Paso 1</li>
    <li>Paso 2</li>
</ol>
```

---

# 💬 Citas y referencias

Las citas sirven para mostrar frases importantes o referencias de autores.

| Etiqueta | Función |
|----------|----------|
| `<blockquote>` | Cita en bloque |
| `<cite>` | Nombre del autor o referencia |

## 💻 Ejemplo

```html
<blockquote>
"La práctica hace al maestro."
</blockquote>

<cite>Autor desconocido</cite>
```

---

# 💻 Código y texto técnico

Estas etiquetas sirven para mostrar código HTML o programación dentro de la página.

| Etiqueta | Función |
|----------|----------|
| `<code>` | Mostrar código |
| `<pre>` | Mantener espacios y saltos |

## 💻 Ejemplo

```html
<pre>
<code>
<h1>Hola Mundo</h1>
</code>
</pre>
```

---

# 📏 Líneas y saltos

Sirven para separar contenido o realizar saltos de línea.

| Etiqueta | Función |
|----------|----------|
| `<hr>` | Línea horizontal |
| `<br>` | Salto de línea |

## 💻 Ejemplo

```html
<p>Hola</p>

<hr>

<p>
Bienvenido<br>
a HTML
</p>
```