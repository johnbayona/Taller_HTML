# Documento de Ejercicios de Clase

## Informacion general

- Skill: HTML + CSS
- Clase: 5
- Duracion estimada: 3 horas
- Tema central: Tipografia, Representacion de Datos y Modelo de Cajas
- Nivel: Formacion inicial

## Proposito de la practica

En esta practica los estudiantes aplicaran propiedades CSS para mejorar la lectura, la organizacion visual y el control del espacio en componentes HTML. Trabajaran tipografia, alineacion, decoracion de texto, tablas, bordes, bordes redondeados, `padding`, `margin`, `overflow` y modelo de cajas. La practica conecta los selectores vistos en la clase anterior con el diseno visual y estructural de componentes.

## Ejercicio 1: Tabla academica estilizada con tarjeta tipografica

### Objetivo

Construir una seccion academica que combine una tarjeta introductoria con jerarquia tipografica y una tabla HTML estilizada mediante CSS.

### Contexto

Un sitio academico necesita presentar informacion de un curso o modulo de forma clara. Para lograrlo, se requiere una tarjeta inicial que explique el tema y una tabla organizada con datos como sesiones, temas, duracion y responsable. El objetivo es mejorar la lectura usando propiedades tipograficas y estilos visuales aplicados con CSS externo.

### Instrucciones paso a paso

1. Crea una carpeta llamada `clase-5-tipografia-tablas` con los archivos `index.html` y `styles.css`.
2. Enlaza el archivo CSS externo desde el `head` del documento HTML.
3. En `index.html`, crea una tarjeta introductoria con titulo, subtitulo, parrafo corto y texto destacado.
4. Debajo de la tarjeta, crea una tabla academica con minimo cuatro columnas: sesion, tema, duracion y responsable.
5. Agrega minimo cuatro filas de informacion en la tabla.
6. En `styles.css`, aplica propiedades tipograficas: `font-family`, `font-size`, `font-weight`, `text-align`, `line-height`, `text-transform` o `text-decoration`.
7. Estiliza la tarjeta usando `padding`, `margin`, `border`, `border-radius` y color de fondo.
8. Estiliza la tabla usando `border-collapse`, bordes, `padding`, alineacion de texto y encabezados diferenciados.
9. Verifica en navegador que la informacion sea legible, ordenada y visualmente coherente.

### Entregable esperado

El estudiante debe entregar la carpeta del proyecto con `index.html`, `styles.css`, evidencia visual en navegador y codigo organizado e indentado.

### Criterios de logro

| Criterio | Cumple | Observaciones |
|---|---|---|
| Comprende el objetivo del ejercicio |  |  |
| Enlaza correctamente el archivo CSS externo |  |  |
| Aplica jerarquia tipografica en la tarjeta |  |  |
| Estiliza la tabla con bordes, padding y alineacion |  |  |
| Usa `margin`, `padding` y `border-radius` correctamente |  |  |
| Presenta una solucion ordenada |  |  |
| Explica su proceso con claridad |  |  |

## Ejercicio 2: Laboratorio del modelo de cajas

### Objetivo

Comparar visualmente el comportamiento de `content`, `padding`, `border`, `margin`, `border-radius` y `overflow` en diferentes bloques HTML.

### Contexto

En CSS, cada elemento se representa como una caja compuesta por contenido, relleno, borde y margen. Comprender este modelo permite controlar el espacio interno y externo de los elementos, evitar desbordamientos y construir interfaces mas ordenadas.

### Instrucciones paso a paso

1. Crea una carpeta llamada `laboratorio-box-model` con los archivos `box.html` y `box.css`.
2. Enlaza el archivo CSS externo desde `box.html`.
3. Crea minimo cinco bloques `div`, cada uno con una clase diferente.
4. En cada bloque, escribe un titulo corto y un parrafo explicando que propiedad se esta demostrando.
5. En `box.css`, aplica estilos base a todos los bloques: ancho fijo, color de fondo, tipografia legible y separacion visual.
6. Modifica cada bloque para evidenciar una propiedad diferente: contenido, `padding`, `border`, `margin`, `border-radius` y `overflow`.
7. Prueba valores diferentes de `overflow`: `visible`, `hidden`, `scroll` y `auto`.
8. Agrega comentarios en el CSS explicando que sucede en cada caso.
9. Abre el archivo en navegador y compara visualmente los cambios.

### Entregable esperado

El estudiante debe entregar `box.html`, `box.css`, evidencia visual del laboratorio en navegador y comentarios CSS explicando las diferencias entre contenido, relleno, borde, margen y desbordamiento.

### Criterios de logro

| Criterio | Cumple | Observaciones |
|---|---|---|
| Comprende el objetivo del ejercicio |  |  |
| Representa visualmente las partes del modelo de cajas |  |  |
| Aplica `padding`, `margin`, `border` y `border-radius` correctamente |  |  |
| Experimenta con `overflow` y explica su comportamiento |  |  |
| Documenta el codigo con comentarios CSS |  |  |
| Presenta una solucion ordenada |  |  |
| Explica su proceso con claridad |  |  |

## Reto de profundizacion

### Nombre del reto

Panel de datos academicos con tipografia y modelo de cajas

### Descripcion

Construye una pagina tipo panel academico que presente informacion de un curso, modulo o evento. La pagina debe integrar una tarjeta principal, una tabla estilizada, una lista de recomendaciones y una seccion donde se evidencie el modelo de cajas.

### Condiciones

- Debe usar HTML5 y CSS externo.
- Debe incluir una tarjeta introductoria con jerarquia tipografica.
- Debe incluir una tabla con minimo cinco filas.
- Debe incluir una lista de recomendaciones o recursos.
- Debe aplicar `font-family`, `font-size`, `font-weight`, `text-align` y `line-height`.
- Debe aplicar `border`, `border-radius`, `padding` y `margin`.
- Debe incluir al menos un elemento con contenido largo controlado con `overflow`.
- Debe incluir comentarios CSS explicando minimo tres decisiones de estilo.
- El codigo debe estar indentado y organizado.

### Entregable esperado

Una carpeta llamada `reto-panel-datos-css` con `index.html`, `styles.css`, captura o evidencia de la pagina en navegador y una explicacion escrita de 5 a 8 lineas sobre como se aplicaron tipografia, representacion de datos y modelo de cajas.

### Criterios de evaluacion

| Criterio | Nivel esperado |
|---|---|
| Autonomia | Construye el panel con estructura propia y decisiones visuales coherentes. |
| Aplicacion tecnica | Usa correctamente propiedades tipograficas, estilos de tabla y modelo de cajas. |
| Claridad de entrega | Presenta archivos ordenados, nombres claros y evidencia visual. |
| Mejora frente a los ejercicios guiados | Integra los conceptos en una pagina mas completa y mejor estructurada. |
