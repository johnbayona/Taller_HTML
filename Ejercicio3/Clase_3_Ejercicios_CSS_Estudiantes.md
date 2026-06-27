# Documento de Ejercicios de Clase

## Informacion general

- Skill: HTML + CSS
- Clase: 3
- Duracion estimada: 3 horas
- Tema central: Introduccion, Cascada y Estilos Visuales con CSS
- Nivel: Formacion inicial

## Proposito de la practica

En esta practica los estudiantes aplicaran estilos CSS a documentos HTML para transformar estructuras basicas en interfaces visualmente mas claras. Trabajaran colores, fondos, herencia, gradientes, imagenes de fondo, variables, cascada y opacidad. La practica conecta la estructura HTML construida en clases anteriores con la presentacion visual propia de CSS.

## Ejercicio 1: Tarjeta visual con colores, herencia, gradiente e imagen de fondo

### Objetivo

Construir una tarjeta visual de perfil o presentacion usando CSS externo, colores, herencia, clases, gradiente e imagen de fondo.

### Contexto

Un sitio web necesita una tarjeta de presentacion para mostrar informacion basica de una persona, producto, servicio o evento. La tarjeta debe tener estructura HTML clara y estilos CSS que mejoren su apariencia visual sin modificar el significado del contenido.

### Instrucciones paso a paso

1. Crea una carpeta llamada `clase-3-css` con los archivos `index.html` y `styles.css`.
2. En `index.html`, construye la estructura base HTML5 y enlaza el archivo CSS externo usando:
   ```html
   <link rel="stylesheet" href="styles.css">
   ```
3. Dentro del `body`, crea una seccion principal con una tarjeta que incluya:
   - Titulo principal.
   - Subtitulo o descripcion corta.
   - Lista de habilidades, caracteristicas o temas.
   - Boton o enlace de accion.
4. En `styles.css`, define estilos generales para `body`, aplicando una fuente base y un color de texto que pueda heredarse en los elementos internos.
5. Crea una clase para la tarjeta, por ejemplo `.card`, y aplica:
   - `background-color` o `background-image`.
   - `linear-gradient()`.
   - `background-size`.
   - `background-position`.
   - `background-repeat`.
   - `padding`.
   - `border-radius`.
6. Agrega una clase para el boton o enlace, por ejemplo `.card__button`, y aplica color de fondo, color de texto y espaciado.
7. Verifica en el navegador que los estilos se apliquen correctamente desde el archivo externo.
8. Ajusta los colores para que el texto sea legible sobre el fondo.

### Entregable esperado

El estudiante debe entregar la carpeta del proyecto con:

- `index.html`.
- `styles.css`.
- Captura de la tarjeta visual abierta en navegador o evidencia equivalente.
- Codigo organizado e indentado.

### Criterios de logro

| Criterio | Cumple | Observaciones |
|---|---|---|
| Comprende el objetivo del ejercicio |  |  |
| Enlaza correctamente el archivo CSS externo |  |  |
| Aplica colores, fondo, gradiente e imagen de fondo |  |  |
| Usa clases CSS de forma clara y ordenada |  |  |
| Mantiene legibilidad entre fondo y texto |  |  |
| Presenta una solucion ordenada |  |  |
| Explica su proceso con claridad |  |  |

## Ejercicio 2: Laboratorio de cascada, variables y opacidad

### Objetivo

Experimentar con reglas CSS en conflicto, variables CSS y opacidad para comprender que estilo prevalece y como se comportan las propiedades visuales.

### Contexto

En un proyecto real es comun que varios estilos afecten un mismo elemento. CSS resuelve estos conflictos mediante reglas de cascada, orden, importancia y especificidad. Este laboratorio permite observar esos comportamientos con ejemplos controlados.

### Instrucciones paso a paso

1. Crea un archivo `laboratorio.html` y enlaza un archivo externo llamado `laboratorio.css`.
2. En `laboratorio.html`, crea minimo cuatro bloques `div` con clases diferentes, por ejemplo:
   - `.box`
   - `.box featured`
   - `.box transparent`
   - `.box variable`
3. En `laboratorio.css`, define variables globales en `:root`, por ejemplo:
   ```css
   :root {
     --color-principal: #1e40af;
     --color-secundario: #f97316;
     --color-texto: #ffffff;
   }
   ```
4. Aplica una regla general para `.box` con color de fondo, color de texto, margen y padding.
5. Crea reglas adicionales que entren en conflicto con la regla general. Por ejemplo:
   ```css
   .box {
     background-color: blue;
   }

   .featured {
     background-color: orange;
   }

   .box.featured {
     background-color: purple;
   }
   ```
6. Agrega un bloque que use variables CSS mediante `var()`.
7. Agrega un bloque con `opacity` y otro con fondo usando canal alfa, por ejemplo `rgb(0 0 0 / 50%)` o `rgba(0, 0, 0, 0.5)`.
8. Compara visualmente la diferencia entre usar `opacity` y usar un fondo con transparencia.
9. Agrega comentarios CSS explicando que regla gana en cada caso y por que.
10. Abre el archivo con Live Server o en navegador y valida los resultados.

### Entregable esperado

El estudiante debe entregar:

- `laboratorio.html`.
- `laboratorio.css`.
- Evidencia visual del laboratorio en navegador.
- Comentarios en el CSS donde explique los conflictos de cascada, uso de variables y diferencia entre opacidad y transparencia de fondo.

### Criterios de logro

| Criterio | Cumple | Observaciones |
|---|---|---|
| Comprende el objetivo del ejercicio |  |  |
| Identifica conflictos entre reglas CSS |  |  |
| Usa variables CSS con `:root` y `var()` |  |  |
| Diferencia `opacity` de fondos con canal alfa |  |  |
| Documenta el codigo con comentarios CSS |  |  |
| Presenta una solucion ordenada |  |  |
| Explica su proceso con claridad |  |  |

## Reto de profundizacion

### Nombre del reto

Landing visual con CSS externo, gradiente, variables y cascada controlada

### Descripcion

Construye una pagina tipo landing sencilla para promocionar un curso, evento, producto o servicio. La pagina debe integrar una seccion principal tipo hero, una tarjeta visual, variables CSS, imagen o gradiente de fondo, bloques con opacidad y reglas donde se evidencie la cascada.

### Condiciones

- Debe usar HTML5 y CSS externo.
- Debe incluir minimo tres secciones: hero, beneficios y llamado a la accion.
- Debe definir minimo tres variables CSS en `:root`.
- Debe usar minimo un `linear-gradient()`.
- Debe usar `background-image`, `background-size`, `background-position` o `background-repeat`.
- Debe incluir al menos un caso comentado donde una regla CSS sobrescriba otra.
- Debe incluir un ejemplo de `opacity` y otro de fondo con canal alfa.
- El codigo debe estar indentado y comentado en las partes clave.

### Entregable esperado

Una carpeta llamada `reto-landing-css` con:

- `index.html`.
- `styles.css`.
- Captura o evidencia de la pagina en navegador.
- Breve explicacion escrita de 5 a 8 lineas sobre como se aplicaron cascada, variables y estilos visuales.

### Criterios de evaluacion

| Criterio | Nivel esperado |
|---|---|
| Autonomia | Construye la pagina con estructura propia y decisiones visuales coherentes. |
| Aplicacion tecnica | Usa correctamente CSS externo, variables, cascada, gradientes, fondos y opacidad. |
| Claridad de entrega | Presenta archivos ordenados, nombres claros y evidencia visual. |
| Mejora frente a los ejercicios guiados | Integra los conceptos en una pagina mas completa y con mayor criterio visual. |
