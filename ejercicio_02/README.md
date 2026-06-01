# Instrucciones 
1. van a crear un index.html 
2. escoger una pagina web de su preferencia 
3. estructurar con los elemntos semanticos de html 
   la pagina web selecionada 

# ESTRUCTURA DE UNA PÁGINA WEB DE FÚTBOL LIBRE TV

## INTRODUCCIÓN

La página mostrada en la imagen corresponde a un sitio web de transmisión de eventos deportivos llamado **“Fútbol Libre TV”**. Su diseño es simple, ordenado y fácil de navegar. La estructura está organizada en diferentes secciones que permiten mostrar información deportiva y facilitar la búsqueda de partidos.

---

# 1. ENCABEZADO (HEADER)

La parte superior de la página corresponde al encabezado principal.

En esta sección aparecen:

* El nombre o logo del sitio: **“Fútbol Libre”**
* Un menú de navegación horizontal con enlaces deportivos.

### Canales visibles:

* L1MAX
* DirecTV Sports
* ESPN1
* ESPN2
* ESPN3
* Fox Sports
* GOLPERU

### Función del encabezado:

* Identificar el sitio web.
* Permitir acceso rápido a diferentes canales deportivos.
* Organizar la navegación principal.

### Etiquetas HTML que normalmente se usan:

* `<header>`
* `<nav>`
* `<a>`

---

# 2. CONTENIDO PRINCIPAL

Debajo del encabezado se encuentra el contenido principal de la página.

Aquí aparece:

## Título principal:

**“Fútbol Libre TV”**

El título está centrado y resaltado con un color verde oscuro.

## Descripción:

Se muestra un pequeño texto informativo explicando que el sitio permite ver partidos de fútbol online y eventos deportivos internacionales.

### Función:

* Informar al usuario sobre el propósito de la página.
* Presentar el contenido principal del sitio.

### Etiquetas HTML utilizadas:

* `<main>`
* `<section>`
* `<h1>`
* `<p>`

---

# 3. ÁREA DE BÚSQUEDA

Debajo de la descripción aparece una sección para buscar eventos deportivos.

Esta parte contiene:

## a) Caja de búsqueda

Permite escribir el nombre de un evento o partido.

Texto visible:
**“Buscar por evento”**

## b) Menú desplegable

Permite seleccionar más eventos deportivos.

Texto visible:
**“-- MAS EVENTOS --”**

### Función:

* Facilitar la búsqueda rápida de partidos.
* Filtrar información deportiva.

### Etiquetas HTML utilizadas:

* `<form>`
* `<input>`
* `<select>`
* `<option>`

---

# 4. SECCIÓN DE AGENDA

Luego aparece una barra horizontal verde con el texto:

## “Agenda - 29 de mayo de 2026”

Esta sección funciona como un organizador de programación deportiva.

### Función:

* Separar visualmente los eventos.
* Mostrar la fecha de la agenda deportiva.

### Etiquetas HTML utilizadas:

* `<div>`
* `<section>`
* `<h2>`

---

# 5. LISTA DE PARTIDOS

La mayor parte de la página está ocupada por la lista de eventos deportivos.

Cada fila contiene:

* Hora del evento.
* Nombre del torneo.
* Equipos participantes.

### Ejemplos visibles:

* Monza vs Catanzaro
* Bosnia-Herzegovina vs Macedonia del Norte
* Atlético Grau vs Deportivo Moquegua
* Cobresal vs Ñublense

### Organización visual:

Los partidos están ordenados en filas horizontales con líneas divisorias.

### Función:

* Mostrar la programación deportiva del día.
* Facilitar la lectura de horarios y encuentros.

### Etiquetas HTML utilizadas:

* `<table>`
* `<tr>`
* `<td>`

También podría construirse usando:

* `<div>`
* `<span>`

---

# 6. DISEÑO VISUAL (CSS)

La página utiliza un diseño limpio y sencillo.

## Colores principales:

* Verde
* Blanco
* Gris claro

## Características del diseño:

* Menú horizontal.
* Contenido centrado.
* Bordes suaves.
* Espaciado ordenado.
* Tipografía simple y legible.

### Propiedades CSS utilizadas:

* `display:flex`
* `margin`
* `padding`
* `background`
* `border`
* `font-size`
* `width`

---

# 7. DISEÑO RESPONSIVO

La estructura probablemente utiliza técnicas responsivas para adaptarse a diferentes dispositivos.

## Compatible con:

* Computadoras
* Tablets
* Celulares

### Técnicas utilizadas:

* Flexbox
* Medidas porcentuales (`%`)
* Media Queries

### Función:

Permitir que la página se vea correctamente en cualquier tamaño de pantalla.

---

# RESUMEN DE LA ESTRUCTURA HTML

La estructura general de la página sería:

* HTML

  * HEAD
  * BODY

    * HEADER

      * Logo
      * Menú
    * MAIN

      * Título
      * Descripción
      * Buscador
      * Agenda
      * Lista de partidos
    * FOOTER (si existe)

---

# CONCLUSIÓN

La página de “Fútbol Libre TV” presenta una estructura web moderna y organizada. Utiliza encabezado, menú de navegación, buscador y una lista de eventos deportivos distribuidos de manera clara. Su diseño facilita que el usuario encuentre rápidamente partidos y canales deportivos mediante una interfaz sencilla, visual y fácil de usar.
