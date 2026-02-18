# 🧪 Guía paso a paso – Página de listas y tabla con acciones

## 🎯 Objetivo

Construir una página web que contenga:

- Listas ordenadas y no ordenadas  
- Una tabla con `colspan` y `rowspan`

---

## 🔹 PARTE 1 — Crear la estructura del proyecto

1. Descarga el proyecto de ejemplo con la carpeta principal.  
2. Abre la carpeta desde Visual Studio Code.  
3. Accede al archivo:

index.html

---

## 🔹 PARTE 2 — Estructura base HTML

Abrir `index.html` y verificar que tenga:

- La estructura básica del documento.
- La etiqueta `<title>` con el texto **Tablas y listas**.
- La conexión a la hoja de estilos `styles/style.css`.
- La sección `<body>` vacía para agregar el contenido.

---

## 🔹 PARTE 3 — Crear la primera lista (ordenada)

Debajo del `<body>`:

1. Agregar un título con el texto:  
   **Lenguajes que quiero aprender**.
2. Crear una lista ordenada.
3. Agregar los siguientes elementos en este orden:
   - JavaScript
   - Python
   - PHP

---

## 🔹 PARTE 4 — Crear la segunda lista (no ordenada)

Debajo de la lista anterior:

1. Agregar un título con el texto:  
   **Mis hobbies**.
2. Crear una lista no ordenada.
3. Agregar los siguientes elementos:
   - Leer
   - Escuchar música
   - Hacer deporte

---

## 🔹 PARTE 5 — Crear el título de la tabla

Antes de la tabla agregar un encabezado con el texto:

**Estudiantes**

---

## 🔹 PARTE 6 — Crear la estructura de la tabla

1. Crear la etiqueta `<table>`.
2. Dentro de la tabla agregar las secciones:
   - `<thead>`
   - `<tbody>`

---

## 🔹 PARTE 7 — Crear la fila con COLSPAN

Dentro de `<thead>`:

1. Crear una fila.
2. Agregar una celda de encabezado que ocupe **5 columnas**.
3. Escribir el texto:  
   **Listado de estudiantes**.

---

## 🔹 PARTE 8 — Crear la fila de encabezados

En una nueva fila dentro de `<thead>` agregar los títulos:

- Nombre  
- Apellido  
- Carrera  
- Semestre  
- Acciones  

---

## 🔹 PARTE 9 — Crear la primera fila de datos

Dentro de `<tbody>` crear una fila con:

- **Nombre:** Ana  
- **Apellido:** López  
- **Carrera:** Ingeniería de Sistemas  
- **Semestre:** 5  

Aplicar `rowspan="2"` en la celda de **Ingeniería de Sistemas**.

En **Acciones** agregar un botón que muestre:  
**Editar registro 1**.

---

## 🔹 PARTE 10 — Crear la segunda fila

Crear una nueva fila con:

- **Nombre:** Carlos  
- **Apellido:** Pérez  
- **Semestre:** 3  

⚠ No agregar la celda de carrera porque está combinada con la fila anterior.

En **Acciones** agregar un botón que muestre:  
**Editar registro 2**.

---

## 🔹 PARTE 11 — Crear la tercera fila normal

Crear otra fila con:

- **Nombre:** María  
- **Apellido:** Gómez  
- **Carrera:** Informática  
- **Semestre:** 7  

En **Acciones** agregar un botón que muestre:  
**Editar registro 3**.

---

## 🔹 PARTE 12 — Cerrar correctamente la estructura

Verificar que estén cerradas todas las etiquetas:

- `</tbody>`
- `</table>`
- `</body>`
- `</html>`

---

## 🔹 PARTE 13 — Guardar y probar

Abrir en el navegador y verificar:

- ✅ Listas visibles  
- ✅ Tabla con 5 columnas  
- ✅ Título superior ocupando todo el ancho  
- ✅ Ingeniería de Sistemas en dos filas  
- ✅ Botones funcionando