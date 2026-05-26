# HTML
Lenguaje de marcado de texto, es la parte que nos permite estructurar nuestra pagina web, 
es como el esqueleto de nuestra apicacion .
Su principal objetivo es darle formato semantico a nuestra informacion a travez de uso 
de 'elementos' que esta a su vez esta conformado por 'etiquetas' de apertura y cierre y 'contenido'
>[!TIP] En algunos casos encontraremos los 'elementos' huerfano estos solo estan conformados
por una sola etiqueta.

## Estructura de un elemento en HTML


## Estructura fundmental del documento HTML 
- <!DOCTYPE html> - Declaramos el tipo de documento, este elemento huerfano indica al navegador 
que el documento con el que se esta trabajando y que debera renderizar es 'html',
**siempre debe estar en la primera linea**
- '<html></html>' - Elemento raiz, envuelve todo el contenido de la pagina HTML, este elemento tiene 
dos hijos principales.
- '<head></head>' -Elemento de configuracion, contiene informacion importante sobre el documento como
(titulo,enlaces css, informacion para motores de busqueda, descripcion entre otros).
 - '<title></title>' - Elemento de titulo de pagina, es el hijo de 'head' y define el titulo
que aparecera en la pestaña del navegador
- '<body></body>' -


## Estructura de contenido semantico (secciones principales)

Las etiquetas semánticas en HTML permiten organizar mejor el contenido de una página web.  
Su objetivo es que tanto los navegadores como los desarrolladores entiendan la función de cada sección del sitio web.

### Principales etiquetas semánticas

- `<header></header>`  
  Representa la cabecera principal de la página o de una sección.  
  Generalmente contiene:
  - Logo
  - Título
  - Menú de navegación
  - Información introductoria
  
  - `<nav></nav>`  
  Define una sección de navegación.  
  Contiene enlaces que permiten desplazarse entre páginas o secciones del sitio web.
---
- `<main></main>`  
  Representa el contenido principal del documento HTML.  
  Dentro de esta etiqueta se coloca la información más importante de la página.  
  Solo debe existir un `main` por documento.
---
- `<section></section>`  
  Agrupa contenido relacionado dentro de una misma temática.  
  Se utiliza para dividir la página en partes organizadas.
---
- `<article></article>`  
  Representa contenido independiente y autónomo.  
  Ejemplos:
  - Noticias
  - Publicaciones
  - Blogs
  - Comentarios
---
- `<aside></aside>`  
  Contiene información complementaria o secundaria relacionada con el contenido principal.  
  Por ejemplo:
  - Publicidad
  - Enlaces relacionados
  - Barra lateral
---
- `<footer></footer>`  
  Representa el pie de página del sitio web o de una sección.  
  Normalmente contiene:
  - Derechos de autor
  - Información de contacto
  - Redes sociales
  - Enlaces adicionales
  
  # Estructura de Texto en HTML

HTML permite organizar y dar significado al contenido de una página web mediante diferentes etiquetas de texto.  
Estas etiquetas ayudan a crear títulos, párrafos, listas, citas, fragmentos de código y mucho más.

---

## Jerarquía de Encabezados

### Descripción
Los encabezados en HTML permiten organizar la información según su importancia.  
Existen 6 niveles de encabezados:

- `<h1>` → Título principal
- `<h2>` → Subtítulos
- `<h3>` → Subtemas
- `<h4>` a `<h6>` → Temas secundarios

Los encabezados ayudan a mejorar la lectura y la estructura de una página web.

### Ejemplo
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Jerarquía de Encabezados</title>
</head>
<body>

    <h1>Título Principal</h1>
    <h2>Subtítulo</h2>
    <h3>Subtema</h3>
    <h4>Detalle</h4>
    <h5>Información Extra</h5>
    <h6>Nota Final</h6>

</body>
</html>
```

---

# Párrafos y Énfasis

## Descripción
Los párrafos se crean con la etiqueta `<p>` y sirven para escribir textos.

Etiquetas de énfasis:
- `<strong>` → Texto importante en negrita
- `<em>` → Texto en cursiva
- `<mark>` → Texto resaltado
- `<small>` → Texto pequeño

Estas etiquetas ayudan a resaltar información importante dentro del contenido.

### Ejemplo
```html
<p>La comida peruana es muy reconocida.</p>

<p>
    El <strong>pollo a la brasa</strong> es uno de los platos más famosos.
</p>

<p>
    Es una comida muy <em>deliciosa</em>.
</p>

<p>
    El ingrediente principal es el <mark>pollo</mark>.
</p>

<p>
    <small>Receta tradicional peruana.</small>
</p>
```

---

# Listas

## Descripción
Las listas permiten organizar información de manera ordenada.

Tipos de listas:
- `<ul>` → Lista desordenada
- `<ol>` → Lista ordenada
- `<li>` → Elementos de lista

Son útiles para mostrar ingredientes, pasos o características.

### Ejemplo
```html
<h2>Ingredientes</h2>

<ul>
    <li>Pollo</li>
    <li>Papas</li>
    <li>Arroz</li>
</ul>

<h2>Preparación</h2>

<ol>
    <li>Lavar los ingredientes</li>
    <li>Cocinar el pollo</li>
    <li>Servir caliente</li>
</ol>
```

---

# Citas y Referencias

## Descripción
Las citas permiten mostrar frases importantes o referencias.

Etiquetas:
- `<blockquote>` → Cita larga
- `<q>` → Cita corta

### Ejemplo
```html
<blockquote>
    "La cocina es el corazón del hogar."
</blockquote>

<p>
    El chef comentó:
    <q>La comida peruana es una de las mejores del mundo.</q>
</p>
```

---

# Código y Texto Técnico

## Descripción
HTML permite mostrar código usando etiquetas especiales.

Etiquetas:
- `<code>` → Fragmentos de código
- `<pre>` → Conserva espacios y saltos

### Ejemplo
```html
<pre>
<code>
body{
    background-color: lightyellow;
}
</code>
</pre>
```

---

# Líneas y Saltos

## Descripción
Estas etiquetas ayudan a ordenar visualmente el contenido.

Etiquetas:
- `<br>` → Salto de línea
- `<hr>` → Línea horizontal

### Ejemplo
```html
<p>
    Nombre: Maycol <br>
    Curso: Diseño Web
</p>

<hr>

<p>Fin del contenido.</p>
```
---
# css (cascading style sheet)
cascada de hojas de estilo , es el documento que nos permite darle estilo a nuestros elementos , posicionar , escalar, posicionar, escalar, color y trancisiones.
## Como aplicar css a nuestro documento html
### 1. en linea
este manera de aplicar css es haciendo uso de los atributos de un elemnto en este caso en especial 
usando el atributo `style`

```html
<p style="color:pink;size:23px">este es el texto </p>
```
>[!TIP] en el caso de los embebidos y los de archivo externo hay que entender sobre selectores:
son manera de como yo identifico un elemnto dentro de un documento html, selector por etiqueta
id y clase, en el diseño web se recomienda solo usar los selectores de tipo clase.
### 2. embebidos
este tipo de aplicar estilo nos permite hacer uso de la etiqueta `style` para poder estilar
nuestrs elementos, por convencion esta etiqueta al ser de configuracion se debe usar 
en 
### 3. archivo externo  

