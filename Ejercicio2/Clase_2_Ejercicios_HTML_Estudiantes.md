# Documento de Ejercicios de Clase

## Informacion general

- Skill: Guia HTML+CSS
- Clase: 2
- Duracion estimada: 3 horas
- Tema central: HTML para la Presentacion y Recoleccion de Informacion
- Nivel: Formacion inicial

## Proposito de la practica

En esta practica los estudiantes aplicaran etiquetas HTML para organizar informacion y recolectar datos. Construiran una tabla academica con listas internas para representar temas por bloque y un formulario basico de registro con campos comunes. El objetivo es que comprendan como HTML permite presentar datos de forma ordenada y capturar informacion del usuario.

## Ejercicio 1: Tabla de horarios academicos con listas de temas

### Objetivo

Crear una tabla HTML que organice dias, horarios, responsables y temas academicos, incluyendo listas dentro de la columna de temas.

### Contexto

Una institucion necesita publicar el horario de una semana de clases. Cada fila debe mostrar el dia, la hora, el responsable y los temas que se trabajaran. Como algunos bloques tienen mas de un tema, la columna de temas debe usar listas HTML.

### Instrucciones paso a paso

1. Crea una carpeta llamada `tabla-horarios-academicos`.
2. Dentro de la carpeta, crea un archivo llamado `index.html`.
3. Escribe la estructura base del documento HTML5.
4. Agrega un titulo principal con `<h1>` y una breve descripcion con `<p>`.
5. Crea una tabla usando `<table>`.
6. Agrega una fila de encabezados con `<tr>` y `<th>` para: Dia, Hora, Responsable y Temas.
7. Crea minimo cinco filas de contenido usando `<tr>` y `<td>`.
8. En la columna Temas, agrega una lista no ordenada `<ul>` con minimo dos elementos `<li>` por cada fila.
9. Agrega un separador `<hr>` despues de la tabla.
10. Debajo de la tabla, escribe una nota corta usando una etiqueta de cita o referencia vista en clase.

### Entregable esperado

El estudiante debe presentar la carpeta del proyecto con el archivo `index.html` y una demostracion en navegador donde se evidencie la tabla con listas internas en la columna de temas.

### Criterios de logro

| Criterio | Cumple | Observaciones |
|---|---|---|
| Crea correctamente la estructura base de HTML5 |  |  |
| Usa una tabla con encabezados y filas organizadas |  |  |
| Incluye listas dentro de la columna de temas |  |  |
| Aplica correctamente etiquetas `<table>`, `<tr>`, `<th>`, `<td>`, `<ul>` y `<li>` |  |  |
| Presenta el contenido de forma clara y legible |  |  |
| Verifica la pagina en navegador |  |  |

## Ejercicio 2: Formulario basico de registro

### Objetivo

Construir un formulario HTML basico para recolectar datos de registro usando la etiqueta `<form>`, campos `<input>`, atributos principales y boton de envio.

### Contexto

Una actividad academica necesita registrar participantes. Para ello se debe crear un formulario sencillo que solicite informacion personal, datos de contacto y preferencias basicas.

### Instrucciones paso a paso

1. Crea una carpeta llamada `formulario-registro`.
2. Dentro de la carpeta, crea un archivo llamado `index.html`.
3. Escribe la estructura base del documento HTML5.
4. Agrega un titulo principal con `<h1>` y una descripcion del formulario con `<p>`.
5. Crea un formulario usando la etiqueta `<form>`.
6. Agrega campos para nombre completo, correo electronico, telefono y fecha de nacimiento.
7. Usa diferentes tipos de `input`: `text`, `email`, `tel`, `date`, `radio`, `checkbox` y `submit`.
8. Agrega etiquetas `<label>` para identificar cada campo.
9. Usa el atributo `value` en opciones como radio, checkbox o boton de envio.
10. Verifica que el formulario se vea ordenado y que el boton de envio aparezca correctamente.

### Entregable esperado

El estudiante debe presentar la carpeta del proyecto con el archivo `index.html` y una demostracion en navegador donde se evidencie el formulario con sus campos principales.

### Criterios de logro

| Criterio | Cumple | Observaciones |
|---|---|---|
| Usa correctamente la etiqueta `<form>` |  |  |
| Incluye campos de entrada variados |  |  |
| Aplica tipos de `input` segun el dato solicitado |  |  |
| Usa etiquetas `<label>` para mejorar claridad |  |  |
| Aplica el atributo `value` en opciones o boton |  |  |
| Presenta un formulario ordenado y funcional visualmente |  |  |

## Reto de profundizacion

### Nombre del reto

Pagina de inscripcion academica con horario y formulario

### Descripcion

Construye una pagina HTML que integre una tabla de horarios, listas de temas, una seccion de recomendaciones y un formulario de inscripcion. El reto debe unir la presentacion de informacion con la recoleccion de datos del usuario.

### Condiciones

- Debe tener estructura HTML5 completa.
- Debe incluir una tabla con minimo cinco filas.
- La columna de temas debe incluir listas `<ul>` o `<ol>` con elementos `<li>`.
- Debe incluir al menos un separador `<hr>`.
- Debe incluir una cita o referencia.
- Debe incluir un formulario con minimo seis campos.
- El formulario debe usar minimo cinco tipos diferentes de `input`.
- Debe mantener indentacion clara y orden en el codigo.

### Entregable esperado

El estudiante debe entregar una carpeta organizada con `index.html` y una demostracion en navegador de la pagina completa.

### Criterios de evaluacion

| Criterio | Nivel esperado |
|---|---|
| Autonomia | Integra tabla, listas y formulario sin depender de una guia paso a paso completa. |
| Aplicacion tecnica | Usa correctamente etiquetas de presentacion y recoleccion de informacion. |
| Claridad de entrega | Presenta codigo ordenado, indentado y facil de revisar. |
| Mejora frente a los ejercicios guiados | Combina los dos ejercicios en una pagina mas completa y coherente. |
