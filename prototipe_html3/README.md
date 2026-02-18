Aquí tienes tu contenido en Markdown corregido ✅

📌 Solo los bloques de código HTML tienen
html … 
El resto queda como texto normal (ya no “se mete” dentro del código).

⸻


# 🧭 Guía paso a paso – Formulario de registro de estudiante

## 🔹 PASO 1: Descarga de archivos base

Descarga la carpeta con los archivos base de código y abre el fichero:

`index.html`

---

## 🔹 PASO 2: Escribir la estructura básica del documento HTML

Abre `index.html` y escribe:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Formulario</title>
</head>
<body>

</body>
</html>
```

⸻

## 🔹 PASO 3: Conectar la hoja de estilos

Dentro del head agrega:
```html
<link rel="stylesheet" href="styles/style.css">
```
Tu head debe quedar así:
```html
<head>
    <title>Formulario</title>
    <link rel="stylesheet" href="styles/style.css">
</head>
```

⸻

## 🔹 PASO 4: Crear el título de la página

Dentro del body agrega:
```html
<h2>Registro de estudiante</h2>
```

⸻

## 🔹 PASO 5: Crear el formulario

Debajo del título crea el formulario:
```html
<form>
</form>
```

⸻

## 🔹 PASO 6: Campo – Nombre completo

Dentro del form agrega:
	•	Un label
	•	Un input de tipo text para guardar el valor de Nombre completo

⸻

## 🔹 PASO 7: Campo – Correo electrónico

Debajo del campo anterior agrega:
	•	Un label
	•	Un input de tipo email para guardar el Correo electrónico

⸻

## 🔹 PASO 8: Campo – Contraseña

Debajo del campo anterior agrega:
	•	Un label
	•	Un input de tipo password para guardar la Contraseña

⸻

## 🔹 PASO 9: Campo – Fecha de nacimiento

Debajo del campo anterior agrega:
	•	Un label
	•	Un input de tipo date para guardar la Fecha de nacimiento

⸻

## 🔹 PASO 10: Botones de género (radio)

Debajo del campo anterior agrega:
	•	Un label
	•	Dos input de tipo radio para guardar el Género:
	•	Masculino
	•	Femenino

⸻

## 🔹 PASO 11: Lista desplegable de carrera

Debajo del campo anterior agrega:
	•	Un label
	•	Un select con tres opciones:
```html
<option>Ingeniería de Sistemas</option>
<option>Diseño gráfico</option>
<option>Administración de Empresas</option>
```

⸻

## 🔹 PASO 12: Checkbox de términos

Adiciona:
	•	Un salto de línea
	•	Un input de tipo checkbox para:

Acepto los términos y condiciones


⸻

## 🔹 PASO 13: Botón de envío

Adiciona:
	•	Un salto de línea
	•	Un input de tipo submit para enviar el formulario
```html
<input type="submit" value="Enviar formulario">
```
