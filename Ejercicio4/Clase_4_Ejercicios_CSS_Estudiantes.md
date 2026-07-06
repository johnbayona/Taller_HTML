# Documento de Ejercicios de Clase

## Informacion general

- Skill: Guia HTML+CSS
- Clase: 4
- Duracion estimada: 3 horas
- Tema central: Selectores y Reglas en CSS
- Nivel: Formacion inicial

## Proposito de la practica

En esta practica los estudiantes aplicaran selectores CSS para identificar elementos de forma precisa y escribir reglas mas ordenadas. Trabajaran selectores basicos, selectores de atributos, pseudoclases y metodologia BEM. El objetivo es que comprendan como seleccionar elementos sin depender de estilos globales innecesarios y como nombrar clases de forma clara y mantenible.

## Ejercicio 1: Laboratorio de selectores, atributos y pseudoclases

### Objetivo

Crear una pagina HTML con botones, enlaces, formulario, tarjetas y una galeria/lista para aplicar selectores por etiqueta, clase, ID, combinaciones, atributos y pseudoclases.

### Contexto

Un proyecto web necesita aplicar estilos diferentes a elementos comunes sin modificar cada etiqueta una por una. Para lograrlo, se deben usar selectores CSS precisos que permitan afectar grupos, estados, atributos y posiciones dentro de una lista o galeria.

### Instrucciones paso a paso

1. Crea una carpeta llamada `laboratorio-selectores`.
2. Dentro de la carpeta, crea los archivos `index.html` y `styles.css`.
3. Enlaza el archivo CSS externo desde el `head` del HTML.
4. En `index.html`, crea una estructura con:
   - Un encabezado principal con `id`.
   - Una seccion de tarjetas con clases.
   - Un grupo de botones.
   - Una lista o galeria con minimo seis elementos.
   - Un formulario con campos activos y un campo deshabilitado.
   - Varios enlaces con diferentes valores en `href`.
5. En `styles.css`, aplica selectores por etiqueta, por clase y por ID.
6. Crea minimo dos selectores mixtos, por ejemplo `section.card-list` o `button.primary`.
7. Aplica selectores de atributos, por ejemplo:
   - `[disabled]`
   - `[href]`
   - `[href^="https"]`
   - `[href$=".pdf"]`
   - `[type="email"]`
8. Aplica pseudoclases a la lista o galeria:
   - `:first-child`
   - `:last-child`
   - `:nth-child()`
   - `:nth-of-type()`
   - `:empty`
9. Agrega al menos un ejemplo de `:hover` en botones o enlaces.
10. Agrega comentarios CSS explicando que selecciona cada bloque de reglas.
11. Abre el proyecto en navegador y verifica que cada selector produzca un cambio visible.

### Entregable esperado

El estudiante debe presentar la carpeta del proyecto con `index.html`, `styles.css` y una demostracion en navegador donde se evidencien los estilos aplicados mediante selectores, atributos y pseudoclases.

### Criterios de logro

| Criterio | Cumple | Observaciones |
|---|---|---|
| Comprende el objetivo del ejercicio |  |  |
| Usa selectores por etiqueta, clase e ID |  |  |
| Aplica selectores mixtos y de atributos |  |  |
| Usa pseudoclases de posicion y estado |  |  |
| Documenta bloques CSS con comentarios claros |  |  |
| Presenta una solucion ordenada |  |  |
| Explica su proceso con claridad |  |  |

## Ejercicio 2: Refactorizacion de clases con BEM

### Objetivo

Renombrar una estructura HTML con clases genericas usando metodologia BEM y aplicar estilos CSS organizados por bloque, elemento y modificador.

### Contexto

En proyectos reales es comun encontrar clases poco claras como `box`, `title`, `item`, `blue` o `big`. Estas clases funcionan al inicio, pero se vuelven dificiles de mantener. La metodologia BEM ayuda a nombrar los estilos de forma mas descriptiva y ordenada.

### Instrucciones paso a paso

1. Crea una carpeta llamada `refactor-bem`.
2. Dentro de la carpeta, crea `index.html` y `styles.css`.
3. Construye una tarjeta de producto, servicio o perfil con clases inicialmente genericas, por ejemplo:
   - `box`
   - `title`
   - `text`
   - `button`
   - `active`
4. Reescribe las clases usando BEM:
   - Bloque: `.card`
   - Elementos: `.card__title`, `.card__text`, `.card__button`
   - Modificadores: `.card--featured`, `.card__button--primary`
5. Actualiza el HTML para usar las nuevas clases.
6. En `styles.css`, agrupa los estilos por bloque, elementos y modificadores.
7. Crea minimo dos tarjetas: una normal y una destacada con modificador.
8. Aplica estilos diferentes usando el modificador BEM.
9. Agrega comentarios que identifiquen bloque, elementos y modificadores.
10. Verifica en navegador que las tarjetas se muestren correctamente.

### Entregable esperado

El estudiante debe presentar la carpeta del proyecto con `index.html`, `styles.css`, una demostracion en navegador y una breve explicacion de como aplico bloque, elemento y modificador.

### Criterios de logro

| Criterio | Cumple | Observaciones |
|---|---|---|
| Comprende el objetivo del ejercicio |  |  |
| Diferencia bloque, elemento y modificador |  |  |
| Renombra clases genericas usando BEM |  |  |
| Organiza el CSS por secciones claras |  |  |
| Aplica modificadores para variantes visuales |  |  |
| Presenta una solucion ordenada |  |  |
| Explica su proceso con claridad |  |  |

## Reto de profundizacion

### Nombre del reto

Mini catalogo con BEM, atributos y pseudoclases

### Descripcion

Construye un mini catalogo de productos, servicios, cursos o perfiles usando metodologia BEM. La pagina debe incluir tarjetas, enlaces, botones, etiquetas de estado y una lista o galeria con pseudoclases. Tambien debe usar selectores de atributos para diferenciar enlaces, campos o botones segun sus atributos.

### Condiciones

- Debe tener estructura HTML5 completa.
- Debe enlazar un archivo CSS externo.
- Debe incluir minimo cuatro tarjetas.
- Las tarjetas deben usar nomenclatura BEM.
- Debe incluir minimo un bloque, tres elementos y dos modificadores.
- Debe usar selectores por etiqueta, clase, ID y atributos.
- Debe aplicar minimo cuatro pseudoclases.
- Debe incluir comentarios CSS que expliquen las reglas mas importantes.
- El codigo debe estar correctamente indentado.

### Entregable esperado

El estudiante debe entregar una carpeta llamada `reto-catalogo-bem` con `index.html`, `styles.css`, evidencia visual en navegador y una explicacion corta de 5 a 8 lineas sobre los selectores y la estructura BEM usada.

### Criterios de evaluacion

| Criterio | Nivel esperado |
|---|---|
| Autonomia | Construye la pagina con estructura propia y decisiones de seleccion CSS coherentes. |
| Aplicacion tecnica | Usa BEM, selectores basicos, atributos y pseudoclases correctamente. |
| Claridad de entrega | Presenta archivos ordenados, nombres claros y evidencia visual. |
| Mejora frente a los ejercicios guiados | Integra los conceptos en una pagina mas completa y mantenible. |
