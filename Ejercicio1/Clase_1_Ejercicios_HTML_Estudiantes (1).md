# Documento de Ejercicios de Clase

## Informacion general

- Skill: Guia HTML+CSS
- Clase: 1
- Duracion estimada: 3 horas
- Tema central: Fundamentos de HTML: estructura, enlaces y contenido multimedia
- Nivel: Formacion inicial

## Proposito de la practica

En esta practica los estudiantes construiran sus primeras paginas HTML aplicando estructura base, etiquetas principales, comentarios, metadatos y organizacion semantica. El objetivo es que comprendan como el navegador interpreta un documento HTML y como una pagina puede pasar de ser una lista de elementos a una estructura clara, legible y ordenada.

## Ejercicio 1: Mi primera pagina HTML

### Objetivo

Crear una pagina `index.html` funcional usando la estructura base de HTML5, metadatos, titulos, parrafos, etiquetas de texto y comentarios.

### Contexto

Un estudiante inicia su primer proyecto web y necesita construir una pagina sencilla de presentacion personal o academica. La pagina debe estar correctamente estructurada para que pueda abrirse en el navegador mediante Live Server.

### Instrucciones paso a paso

1. Crea una carpeta llamada `mi-primera-pagina-html`.
2. Dentro de la carpeta, crea un archivo llamado `index.html`.
3. Escribe la estructura base del documento: `<!DOCTYPE html>`, `<html>`, `<head>` y `<body>`.
4. Dentro de `<head>`, agrega `charset`, `title`, `description`, `author` y `favicon` si cuentas con un icono disponible.
5. Dentro de `<body>`, agrega un titulo principal con `<h1>`, dos subtitulos con `<h2>` y tres parrafos con `<p>`.
6. Usa al menos tres etiquetas de texto entre: `<strong>`, `<em>`, `<mark>`, `<span>`, `<small>`.
7. Agrega al menos tres comentarios HTML para separar secciones del codigo.
8. Abre el archivo con Live Server y verifica que la pagina cargue correctamente.

### Entregable esperado

El estudiante debe presentar la carpeta del proyecto con el archivo `index.html` y una captura o demostracion en navegador donde se evidencie la pagina funcionando.

### Criterios de logro

| Criterio | Cumple | Observaciones |
|---|---|---|
| Crea correctamente la estructura base de HTML5 |  |  |
| Usa metadatos basicos dentro de `<head>` |  |  |
| Organiza contenido visible dentro de `<body>` |  |  |
| Aplica etiquetas de texto de forma coherente |  |  |
| Usa comentarios para separar secciones |  |  |
| Verifica la pagina en navegador con Live Server |  |  |

## Ejercicio 2: Pagina semantica de noticia

### Objetivo

Construir una pagina tipo noticia usando etiquetas semanticas como `header`, `main`, `section`, `article` y `footer`, diferenciandolas del uso generico de `div`.

### Contexto

Un sitio informativo necesita publicar una noticia sencilla sobre tecnologia, deporte, cultura o vida academica. La pagina debe estar organizada semanticamente para que su estructura sea clara tanto para el navegador como para otros desarrolladores.

### Instrucciones paso a paso

1. Crea una carpeta llamada `noticia-semantica`.
2. Dentro de la carpeta, crea un archivo llamado `index.html`.
3. Escribe la estructura base completa de HTML5.
4. Crea un `<header>` con el nombre del sitio y un pequeno texto introductorio.
5. Crea un `<main>` que contenga un `<article>` con el titulo de la noticia, fecha, autor y contenido principal.
6. Divide el contenido de la noticia en minimo dos `<section>`.
7. Dentro del articulo, agrega al menos una imagen con `<img>` y su atributo `alt`.
8. Agrega un enlace relacionado usando `<a>`.
9. Cierra la pagina con un `<footer>` que incluya informacion de contacto o derechos de autor.
10. Agrega un bloque con `<div>` para un contenido auxiliar y escribe un comentario indicando por que se uso como contenedor generico.

### Entregable esperado

El estudiante debe presentar la carpeta del proyecto con el archivo `index.html`, la imagen usada en una carpeta `images` y una demostracion en navegador de la noticia estructurada.

### Criterios de logro

| Criterio | Cumple | Observaciones |
|---|---|---|
| Usa etiquetas semanticas principales correctamente |  |  |
| Diferencia contenido estructural de contenedores genericos |  |  |
| Incluye imagen con `src` y `alt` |  |  |
| Agrega enlaces funcionales |  |  |
| Mantiene indentacion y anidacion clara |  |  |
| Presenta una noticia legible y ordenada |  |  |

## Reto de profundizacion

### Nombre del reto

Mini portal informativo con navegacion interna

### Descripcion

Construye una pagina HTML mas completa que combine la estructura base, etiquetas de texto, enlaces, multimedia y semantica. El portal debe funcionar como una pagina informativa de una institucion, evento o tema academico, con navegacion interna mediante anclas.

### Condiciones

- Debe tener una estructura HTML5 completa y correctamente indentada.
- Debe incluir `header`, `main`, minimo tres `section`, un `article` y `footer`.
- Debe tener un menu de navegacion con enlaces internos hacia cada seccion.
- Debe incluir minimo una imagen, un enlace externo y un video o iframe.
- Debe usar comentarios HTML para separar las zonas principales del documento.
- Debe incluir al menos cinco etiquetas de texto vistas en clase.

### Entregable esperado

El estudiante debe entregar una carpeta organizada con `index.html`, carpeta `images` si aplica y una demostracion del portal funcionando en navegador.

### Criterios de evaluacion

| Criterio | Nivel esperado |
|---|---|
| Autonomia | Construye la pagina sin depender de una guia paso a paso completa. |
| Aplicacion tecnica | Integra estructura, semantica, enlaces y multimedia correctamente. |
| Claridad de entrega | Presenta carpetas, codigo e indentacion de forma ordenada. |
| Mejora frente a los ejercicios guiados | Combina los conceptos en una pagina mas completa y navegable. |
