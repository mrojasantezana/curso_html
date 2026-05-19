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
