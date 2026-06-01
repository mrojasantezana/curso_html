# UNIDADES DE MEDIDA EN DISEÑO WEB

## ¿Qué son las unidades de medida en diseño web?

Las unidades de medida en diseño web son valores utilizados en HTML y CSS para definir tamaños, espacios, posiciones y dimensiones de los elementos de una página web. Gracias a estas unidades, los diseñadores pueden controlar el ancho, alto, márgenes, textos, imágenes y otros componentes visuales.

Las unidades permiten que una página sea adaptable, ordenada y compatible con diferentes dispositivos como computadoras, tablets y celulares.

---

# TIPOS DE UNIDADES DE MEDIDA

Las unidades de medida en diseño web se dividen en dos grandes grupos:

* Unidades absolutas
* Unidades relativas

---

# 1. UNIDADES ABSOLUTAS

Las unidades absolutas tienen un tamaño fijo y no cambian según el dispositivo o pantalla.

## a) px (Píxeles)

Es la unidad más utilizada en diseño web. Representa un punto en la pantalla.

### Ejemplo:

```css
h1{
    font-size: 32px;
}
```

### Características:

* Tamaño exacto y preciso.
* Muy usado para textos, imágenes y contenedores.
* No cambia según el tamaño de pantalla.

### Ventajas:

* Fácil de controlar.
* Diseño más preciso.

### Desventajas:

* Menos adaptable en dispositivos pequeños.

---

## b) cm (Centímetros)

Representa medidas físicas reales.

### Ejemplo:

```css
div{
    width: 10cm;
}
```

### Uso:

Se utiliza principalmente para impresión.

---

## c) mm (Milímetros)

Unidad física más pequeña que el centímetro.

### Ejemplo:

```css
div{
    margin: 5mm;
}
```

---

## d) in (Pulgadas)

Representa pulgadas físicas.

### Ejemplo:

```css
img{
    width: 2in;
}
```

---

## e) pt (Puntos)

Muy utilizada en documentos e impresión.

### Ejemplo:

```css
p{
    font-size: 12pt;
}
```

---

# 2. UNIDADES RELATIVAS

Las unidades relativas cambian según el tamaño de pantalla, fuente o elemento padre. Son las más recomendadas para páginas modernas y adaptables.

---

## a) % (Porcentaje)

Define tamaños basados en el elemento contenedor.

### Ejemplo:

```css
div{
    width: 50%;
}
```

### Explicación:

El elemento ocupará el 50% del ancho disponible.

### Ventajas:

* Adaptable.
* Muy útil para diseños responsivos.

---

## b) em

Depende del tamaño de fuente del elemento padre.

### Ejemplo:

```css
p{
    font-size: 2em;
}
```

### Explicación:

Si el padre mide 16px, entonces 2em será igual a 32px.

### Ventajas:

* Flexible y escalable.

### Desventajas:

* Puede complicarse en estructuras grandes.

---

## c) rem

Se basa en el tamaño de fuente raíz del documento (`html`).

### Ejemplo:

```css
h1{
    font-size: 3rem;
}
```

### Ventajas:

* Más fácil de controlar que `em`.
* Muy usada en diseño moderno.

---

## d) vw (Viewport Width)

Representa un porcentaje del ancho de la ventana del navegador.

### Ejemplo:

```css
div{
    width: 50vw;
}
```

### Explicación:

El elemento ocupará el 50% del ancho visible del navegador.

---

## e) vh (Viewport Height)

Representa un porcentaje de la altura de la ventana del navegador.

### Ejemplo:

```css
section{
    height: 100vh;
}
```

### Explicación:

El elemento ocupará toda la altura de la pantalla.

---

## f) vmin y vmax

* `vmin`: usa el valor menor entre ancho y alto.
* `vmax`: usa el valor mayor entre ancho y alto.

### Ejemplo:

```css
div{
    font-size: 5vmin;
}
```

---

# IMPORTANCIA DE LAS UNIDADES DE MEDIDA

Las unidades de medida son fundamentales porque permiten:

* Crear diseños adaptables.
* Mejorar la experiencia del usuario.
* Mantener el orden visual.
* Adaptar páginas a celulares y computadoras.
* Mejorar la accesibilidad y lectura.

---

# DISEÑO RESPONSIVO

El diseño responsivo consiste en crear páginas que se adapten automáticamente a diferentes tamaños de pantalla.

Las unidades relativas como `%`, `rem`, `vw` y `vh` ayudan mucho en este tipo de diseño.

### Ejemplo:

```css
.container{
    width: 90%;
}
```

Esto hace que el contenido se adapte mejor en celulares y tablets.

---

# DIFERENCIA ENTRE PX Y REM

| PX                     | REM                                   |
| ---------------------- | ------------------------------------- |
| Tamaño fijo            | Tamaño adaptable                      |
| Menos flexible         | Más flexible                          |
| Diseño exacto          | Mejor para responsive                 |
| No depende del usuario | Respeta configuraciones del navegador |

---

# RECOMENDACIONES

* Usar `px` para detalles pequeños.
* Usar `rem` para textos.
* Usar `%` para tamaños flexibles.
* Usar `vh` y `vw` para pantallas completas.
* Combinar unidades según la necesidad del proyecto.

---

# EJEMPLO COMPLETO EN CSS

```css
body{
    font-size: 16px;
}

.container{
    width: 80%;
    height: 100vh;
    margin: auto;
}

h1{
    font-size: 2rem;
}

p{
    font-size: 1em;
}
```

---

# CONCLUSIÓN

Las unidades de medida en diseño web son esenciales para construir páginas modernas, organizadas y adaptables. Conocer las diferencias entre unidades absolutas y relativas permite desarrollar sitios web más profesionales y compatibles con diferentes dispositivos. Las unidades relativas son las más utilizadas actualmente porque facilitan el diseño responsivo y mejoran la experiencia del usuario.
