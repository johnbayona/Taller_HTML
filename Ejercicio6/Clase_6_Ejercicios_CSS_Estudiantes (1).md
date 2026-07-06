# Documento de Ejercicios de Clase

## Informacion general

- Skill: HTML + CSS
- Clase: 6
- Duracion estimada: 3 horas
- Tema central: Unidades Relativas, Maquetacion y Flexbox
- Nivel: Formacion inicial

## Proposito de la practica

En esta practica los estudiantes aplicaran unidades CSS, propiedades de maquetacion y Flexbox para construir estructuras visuales mas ordenadas. Trabajaran `display`, `position`, unidades relativas, alineacion, distribucion, direccion y comportamiento flexible de elementos. La practica conecta el modelo de cajas visto en la clase anterior con la construccion de layouts adaptables.

## Ejercicio 1: Layout basico con navegacion Flexbox y boton fijo

### Objetivo

Construir una pagina con estructura basica que combine `display`, posicionamiento y una barra de navegacion usando Flexbox.

### Contexto

Una pagina web necesita una estructura inicial con encabezado, navegacion, contenido principal y un boton fijo de accion. El objetivo es organizar los elementos en pantalla usando propiedades de maquetacion y aplicar Flexbox para distribuir los enlaces de navegacion de forma alineada y clara.

### Instrucciones paso a paso

1. Crea una carpeta llamada `clase-6-layout-navbar` con los archivos `index.html` y `styles.css`.
2. Enlaza el archivo CSS externo desde el `head` del documento HTML.
3. En `index.html`, crea la estructura base con `header`, `nav`, `main`, `section`, varias tarjetas de contenido y un boton fijo de accion.
4. Dentro del `nav`, crea una lista de enlaces de navegacion.
5. En `styles.css`, aplica estilos generales al `body`, usando unidades como `%`, `rem`, `vh` o `vw` cuando corresponda.
6. Convierte la navegacion en un contenedor flexible usando `display: flex`.
7. Aplica propiedades Flexbox en la navegacion: `justify-content`, `align-items`, `gap` y `flex-direction`.
8. Usa `display` para comparar elementos `block`, `inline-block` o `flex` dentro de la pagina.
9. Crea un boton fijo usando `position: fixed`, `right`, `bottom` y `z-index`.
10. Agrega una tarjeta o etiqueta con `position: relative` y un elemento interno con `position: absolute`.
11. Verifica en navegador que la navegacion este alineada y que el boton permanezca fijo al hacer scroll.

### Entregable esperado

El estudiante debe entregar la carpeta del proyecto con `index.html`, `styles.css`, evidencia visual de la pagina abierta en navegador y codigo organizado e indentado.

### Criterios de logro

| Criterio | Cumple | Observaciones |
|---|---|---|
| Comprende el objetivo del ejercicio |  |  |
| Enlaza correctamente el archivo CSS externo |  |  |
| Usa `display` para organizar elementos |  |  |
| Construye una navegacion con Flexbox |  |  |
| Aplica `justify-content`, `align-items` y `gap` correctamente |  |  |
| Usa `position: fixed`, `relative` y `absolute` con criterio |  |  |
| Presenta una solucion ordenada |  |  |
| Explica su proceso con claridad |  |  |

## Ejercicio 2: Galeria flexible multilinea

### Objetivo

Construir una galeria de tarjetas usando Flexbox, unidades relativas y comportamiento multilinea con `flex-wrap`.

### Contexto

En muchos sitios web se requiere mostrar tarjetas de productos, servicios, proyectos o recursos. Flexbox permite distribuir estos elementos en filas, controlar su alineacion y permitir que pasen a nuevas lineas cuando el espacio disponible cambia.

### Instrucciones paso a paso

1. Crea una carpeta llamada `galeria-flexible` con los archivos `galeria.html` y `galeria.css`.
2. Enlaza el archivo CSS externo desde `galeria.html`.
3. Crea una seccion principal con titulo, descripcion corta y una galeria.
4. Dentro de la galeria, crea minimo ocho tarjetas. Cada tarjeta debe incluir titulo, descripcion corta, etiqueta o categoria y boton o enlace.
5. En `galeria.css`, define estilos base usando unidades relativas: `%`, `rem`, `vw` y `vh`.
6. Convierte la galeria en contenedor flexible con `display: flex`.
7. Aplica `flex-wrap: wrap`, `justify-content`, `align-items`, `align-content` y `gap`.
8. Ajusta el ancho de las tarjetas usando unidades relativas o porcentajes simples.
9. Usa `order` en al menos dos tarjetas para modificar su orden visual.
10. Cambia temporalmente `flex-direction` entre `row`, `row-reverse`, `column` y `column-reverse` para observar el efecto.
11. Verifica como cambia la galeria al modificar el ancho del navegador.

### Entregable esperado

El estudiante debe entregar `galeria.html`, `galeria.css`, evidencia visual de la galeria en navegador y comentarios CSS breves explicando el uso de `flex-wrap`, `justify-content`, `align-items`, `align-content` y `order`.

### Criterios de logro

| Criterio | Cumple | Observaciones |
|---|---|---|
| Comprende el objetivo del ejercicio |  |  |
| Usa unidades relativas para tamanos y espaciados |  |  |
| Construye una galeria con `display: flex` |  |  |
| Aplica correctamente `flex-wrap` |  |  |
| Usa alineacion en eje principal y eje secundario |  |  |
| Modifica el orden visual de algunos elementos con `order` |  |  |
| Presenta una solucion ordenada |  |  |
| Explica su proceso con claridad |  |  |

## Reto de profundizacion

### Nombre del reto

Landing adaptable con Flexbox

### Descripcion

Construye una pagina tipo landing para presentar un curso, servicio, evento o producto. La pagina debe integrar una barra de navegacion flexible, una seccion principal, una galeria de tarjetas multilinea y un boton fijo de accion.

### Condiciones

- Debe usar HTML5 y CSS externo.
- Debe incluir una barra de navegacion con Flexbox.
- Debe incluir una seccion hero con altura usando `vh`.
- Debe incluir una galeria con minimo seis tarjetas usando `flex-wrap`.
- Debe usar minimo cuatro unidades diferentes entre `px`, `%`, `rem`, `em`, `vw` y `vh`.
- Debe aplicar `justify-content`, `align-items` y `gap`.
- Debe incluir un elemento con `position: fixed`.
- Debe incluir un caso con `position: relative` y un elemento interno con `position: absolute`.
- Debe usar `order` en al menos un elemento flexible.
- Debe incluir comentarios CSS explicando minimo tres decisiones de maquetacion.

### Entregable esperado

Una carpeta llamada `reto-landing-flexbox` con `index.html`, `styles.css`, captura o evidencia de la pagina en navegador y una explicacion escrita de 5 a 8 lineas sobre como se aplicaron unidades, maquetacion y Flexbox.

### Criterios de evaluacion

| Criterio | Nivel esperado |
|---|---|
| Autonomia | Construye la landing con estructura propia y decisiones visuales coherentes. |
| Aplicacion tecnica | Usa correctamente unidades CSS, `display`, posicionamiento y Flexbox. |
| Claridad de entrega | Presenta archivos ordenados, nombres claros, comentarios y evidencia visual. |
| Mejora frente a los ejercicios guiados | Integra los conceptos en una pagina mas completa y adaptable. |
