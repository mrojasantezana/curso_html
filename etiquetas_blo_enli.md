etiquetas de tipo bloque y en linea y como se utiliza,diferencias

# Etiquetas de Tipo Bloque y en Línea en HTML

## Introducción

En HTML, las etiquetas se clasifican principalmente en **etiquetas de bloque** y **etiquetas en línea (inline)**. Esta clasificación determina cómo se muestran los elementos dentro de una página web y cómo interactúan con otros elementos.

---

# 1. Etiquetas de Bloque

Las etiquetas de bloque ocupan **todo el ancho disponible** del contenedor y siempre comienzan en una **nueva línea**.

## Características

- Ocupan el ancho completo del contenedor.
- Comienzan en una nueva línea.
- Se utilizan para estructurar el contenido de la página.
- Pueden contener otras etiquetas de bloque y etiquetas en línea.

## Etiquetas de bloque más comunes

- `<div>`
- `<p>`
- `<h1>` a `<h6>`
- `<section>`
- `<article>`
- `<header>`
- `<footer>`
- `<nav>`
- `<main>`
- `<aside>`
- `<ul>`
- `<ol>`
- `<li>`
- `<table>`
- `<form>`

## Ejemplo

```html
<h1>Mi Página Web</h1>

<p>Este es un párrafo.</p>

<div>
    Este contenido pertenece a un contenedor.
</div>
```

---

# 2. Etiquetas en Línea (Inline)

Las etiquetas en línea ocupan únicamente el espacio necesario para mostrar su contenido y **no generan un salto de línea**.

## Características

- No comienzan en una nueva línea.
- Solo ocupan el espacio necesario.
- Se utilizan para dar formato a palabras o partes de un texto.
- Generalmente contienen texto u otras etiquetas en línea.

## Etiquetas en línea más comunes

- `<span>`
- `<a>`
- `<strong>`
- `<em>`
- `<b>`
- `<i>`
- `<u>`
- `<img>`
- `<small>`
- `<sup>`
- `<sub>`
- `<code>`

## Ejemplo

```html
<p>
Mi nombre es <strong>Maycol</strong> y estudio
<span>Computación e Informática</span>.
</p>
```

---

# ¿Cómo se utilizan?

## Uso de etiquetas de bloque

Se emplean para organizar la estructura de una página web.

```html
<div>
    <h2>Productos</h2>
    <p>Lista de productos disponibles.</p>
</div>
```

En este ejemplo:

- `<div>` agrupa el contenido.
- `<h2>` representa un título.
- `<p>` representa un párrafo.

Cada elemento aparece en una línea diferente.

---

## Uso de etiquetas en línea

Se utilizan para aplicar formato o agregar funcionalidad a una parte específica del contenido.

```html
<p>El precio del producto es <strong>S/ 150</strong>.</p>
```

Otro ejemplo:

```html
<p>
Visita
<a href="https://www.google.com">Google</a>
para realizar búsquedas.
</p>
```

En este caso:

- `<strong>` muestra el texto en negrita.
- `<a>` crea un enlace.

---

# Diferencias entre etiquetas de bloque y etiquetas en línea

| Característica | Etiquetas de Bloque | Etiquetas en Línea |
|----------------|---------------------|--------------------|
| Inician en una nueva línea | Sí | No |
| Ocupan todo el ancho disponible | Sí | No |
| Organizan la estructura de la página | Sí | No |
| Dan formato al contenido | No (principalmente) | Sí |
| Pueden contener otras etiquetas | Sí | Generalmente solo etiquetas en línea |
| Ejemplos | `<div>`, `<p>`, `<section>`, `<h1>` | `<span>`, `<a>`, `<strong>`, `<em>` |

---

# Ejemplo completo

```html
<div>

    <h2>Bienvenido</h2>

    <p>
        Mi nombre es
        <strong>Maycol</strong>
        y estudio
        <span style="color:blue;">Computación e Informática</span>.
    </p>

</div>
```

## Explicación

- `<div>` es una etiqueta de bloque que agrupa todo el contenido.
- `<h2>` es una etiqueta de bloque para el título.
- `<p>` es una etiqueta de bloque para el párrafo.
- `<strong>` es una etiqueta en línea que pone el texto en negrita.
- `<span>` es una etiqueta en línea utilizada para aplicar estilos a una parte del texto.

---

# Conclusión

Las **etiquetas de bloque** permiten organizar y estructurar una página web, ya que ocupan todo el ancho disponible y comienzan en una nueva línea. Por otro lado, las **etiquetas en línea** se utilizan para aplicar formato o agregar funcionalidades a pequeñas partes del contenido sin modificar la estructura general del documento. Comprender la diferencia entre ambos tipos de etiquetas es fundamental para desarrollar páginas web bien organizadas y fáciles de mantener.