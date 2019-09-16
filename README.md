# HTML5
HTML5 es la última versión de HTML.

El término representa dos conceptos diferentes:

* Se trata de una nueva versión de HTML, con nuevos elementos, atributos y comportamientos.
* Contiene un conjunto más amplio de tecnologías que permite a los sitios Web y a las aplicaciones ser más diversas y de gran alcance. A este conjunto se le llama HTML5 y amigos, a menudo reducido a HTML5.

[Más información](https://developer.mozilla.org/es/docs/HTML/HTML5)

## Etiquetas nuevas de HTML5

<img src="/images/HTML4vsHTML5.png" />

## Etiquetas obsoletas

Tag | Descripción
----|-------------
  `<acronym>` | Permite indicar una secuencia de caracteres que componen un acrónimo o abreviatura para una palabra. 
  `<applet>` | Incrusta un applet de Java en el documento.
  `<basefont>` | Establece una fuente, tamaño y color de fuente predeterminados para los otros elementos que descienden de su elemento padre.
  `<big>` | Hace que el texto tenga un tamaño de fuente un nivel mayor que el texto circundante. 
  `<center>` | Muestra su contenido de nivel de bloque o en línea centrado horizontalmente dentro de su elemento contenedor. 
  `<dir>` | Se usa como contenedor para un directorio de archivos y / o carpetas, potencialmente con estilos e íconos aplicados.
  `<font>` | Define el tamaño, el color y la fuente de su contenido.
  `<frame>` | Es un elemento HTML que define un área particular en la que se puede mostrar otro documento HTML.
  `<frameset>` | Se usa para contener elementos `<frame>`.
  `<isindex>` |  Coloca un campo de texto en una página para consultar el documento.
  `<noframes>` | Proporciona contenido que se presentará en los navegadores que no soportan del elemento `<frame>`.
  `<strike>` | Coloca un tachado (línea horizontal) sobre el texto.
  `<tt>` | Crea texto en línea que se presenta utilizando la fuente de monoespacio predeterminada.
  
## Etiqutas nuevas
  
Tag | Descripción
----|-------------
  `<article>` | Define un artículo en un documento
  `<aside>` | Define contenido aparte(aside) del contenido de la página
  `<bdi>` | Aísla una parte del texto que podría estar formateada en una dirección diferente de otro texto fuera de él
  `<details>` | Define detalles adicionales que el usuario puede ver u ocultar
  `<dialog>` | Define un cuadro de diálogo o ventana
  `<figcaption>` | Define un título para un elemento `<figure>`
  `<figure>` | Define contenido autocontenido
  `<footer>` | Define un pie de página para un documento o sección
  `<header>` | Define un encabezado para un documento o sección
  `<main>` | Define el contenido principal de un documento
  `<mark>` | Define texto marcado/resaltado
  `<meter>` | Define una medición escalar dentro de un rango conocido (un medidor)
  `<nav>` | Define enlaces de navegación
  `<progress>` | Representa el progreso de una tarea
  `<rp>` | Define qué mostrar en los navegadores que no admiten anotaciones ruby
  `<rt>` | Define una explicación / pronunciación de los caracteres (para la tipografía de Asia Oriental)
  `<ruby>` | Define una anotación ruby (para la tipografía de Asia oriental)
  `<section>` | Define una sección en un documento
  `<summary>` | Define un encabezado visible para un elemento `<details>`
  `<time>` | Define una fecha/hora
  `<wbr>` | Define un posible salto de línea 
  
## Estructura básica HTML5
  
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

## HTML `<header>`

El elemento `<header>` representa un contenedor para contenido introductorio o un conjunto de enlaces de navegación.

Un elemento `<header>` generalmente contiene:

* Uno o más elementos de encabezado (`<h1>` - `<h6>`)
* Logotipo o icono
* Información de autoría

Puede tener varios elementos `<header>` en un documento.

**Nota**: No se puede colocar una etiqueta `<header>` dentro de un `<footer>`, `<address>` u otro elemento `<header>`.

## HTML Headings `<h1>`...`<h2>`

Los encabezados se definen con las etiquetas `<h1>` a `<h6>`.

`<h1>` define el encabezado más importante. `<h6>` define el encabezado menos importante.

### Ejemplo

```
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

## HTML `<hgroup>`

El elemento HTML `<hgroup>` representa un encabezado de varios niveles para una sección de un documento. Agrupa un conjunto de `<h1>`–`<h6>` elementos.
  
### Ejemplo

```
<hgroup>
    <h1>Cálculo I</h1>
    <h2>Fundamentos</h2>
</hgroup>
<p>Este curso comenzará con una breve introducción sobre el límite de una función. Luego describiremos cómo surge la idea de derivada en los campos de Física y Geometría. Después de eso, explicaremos que la clave para dominar el cálculo es...</p>
```

<hgroup>
    <h1>Cálculo I</h1>
    <h2>Fundamentos</h2>
</hgroup>
<p>Este curso comenzará con una breve introducción sobre el límite de una función. Luego describiremos cómo surge la idea de derivada en los campos de Física y Geometría. Después de eso, explicaremos que la clave para dominar el cálculo es...</p>

## HTML `<nav>`
  
La etiqueta `<nav>` define un conjunto de enlaces de navegación.

Tenga en cuenta que NO todos los enlaces de un documento deben estar dentro de un elemento <nav>. El elemento <nav> está destinado solo para el bloque principal de enlaces de navegación .

## Listas HTML: Desordenadas `<ul>`, Ordenadas `<ol>`, Elementos <li>
  
Una lista desordenada comienza con el tag `<ul>`. Una lista desordenada comienza con el tag `<ul>`. Cada elemento de la lista comienza con la etiqueta `<li>`.

Los elementos de la lista se marcarán con viñetas (pequeños círculos negros) de forma predeterminada en una lista desordenada y con números en una lista ordenada:

### Ejemplo

```
<ul>
  <li>Café</li>
  <li>Te</li>
  <li>Leche</li>
</ul>

<ol>
  <li>Café</li>
  <li>Te</li>
  <li>Leche</li>
</ol>  
```

<ul>
  <li>Café</li>
  <li>Te</li>
  <li>Leche</li>
</ul>  

<ol>
  <li>Café</li>
  <li>Te</li>
  <li>Leche</li>
</ol>
