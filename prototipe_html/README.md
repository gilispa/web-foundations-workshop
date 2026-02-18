# Taller práctico -- Fundamentos de HTML

## 🧪 Guía paso a paso -- Construcción de página web con HTML5 y CSS básico

### 🎯 Objetivo

Construir una página web con estructura semántica

------------------------------------------------------------------------

## 🔹 PARTE 1 --- Crear el archivo base

1️⃣ Descarga el .zip con el proyecto de ejemplo\
2️⃣ Abrir el archivo en Visual Studio Code.

------------------------------------------------------------------------

### 2️⃣ Escribir la estructura básica HTML5

Escribir lo siguiente y **NO modificar las etiquetas**:

``` html
<!DOCTYPE html>
<html>
<head>
    <title>Mi primera página estructurada</title>
</head>
<body>

</body>
</html>
```

Guardar el archivo y abrirlo en el navegador.

------------------------------------------------------------------------

## 🔹 PARTE 2 --- Crear la estructura semántica

Dentro del `<body>` agregar las etiquetas en este orden:

-   `<header>`
-   `<nav>`
-   `<article>`
-   `<aside>`
-   `<p>`
-   `<footer>`

------------------------------------------------------------------------

## 🔹 PARTE 3 --- Construir el HEADER

Dentro del `<header>` escribir:

Programación Web -- Nombre del estudiante

------------------------------------------------------------------------

## 🔹 PARTE 4 --- Construir el menú de navegación

Dentro del `<nav>` agregar una lista no ordenada con 4 enlaces:

-   Inicio\
-   Servicios\
-   Portafolio\
-   Contacto

------------------------------------------------------------------------

## 🔹 PARTE 5 --- Construir el ARTICLE con 3 SECTION

Dentro del `<article>` crear tres `<section>`.

### ✳ SECTION 1

Agregar:

-   Un encabezado de nivel 2 con el texto:\
    Bienvenidos a mi sitio web

-   Un párrafo que contenga:

    -   una palabra en negrita\
    -   una palabra en itálica\
    -   la palabra HTML dentro de un `<span>` en color rojo

### ✳ SECTION 2

Agregar:

-   Un encabezado de nivel 2: ¿Qué es HTML?\
-   Un párrafo con la definición\
-   Un `<blockquote>` con el texto:\
    HTML describe la estructura de una página web.

### ✳ SECTION 3

Agregar:

-   Un encabezado de nivel 2: Pasos para crear una web\

-   Una lista ordenada con:

    1.  Crear el archivo HTML\
    2.  Agregar la estructura básica\
    3.  Visualizar en el navegador

------------------------------------------------------------------------

## 🔹 PARTE 6 --- Crear el ASIDE

Dentro del `<aside>` agregar:

1.  Un título: Recurso recomendado\
2.  Una imagen con la URL:

https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg

------------------------------------------------------------------------

## 🔹 PARTE 7 --- Crear el enlace externo

Dentro del `<p>` (debajo del aside) escribir:

Texto:\
Visita el sitio oficial W3C

La palabra **W3C** debe ser un enlace que abra en otra pestaña hacia:\
https://www.w3.org

------------------------------------------------------------------------

## 🔹 PARTE 8 --- Crear el FOOTER

Dentro del `<footer>` escribir:

2026 -- Desarrollo Web

------------------------------------------------------------------------

## 🔹 PARTE 9 --- Agregar el CSS

Dentro del `<head>`, debajo del `<title>`, agregar la etiqueta:

``` html
<link rel="stylesheet" href="/styles/style.css">
```
