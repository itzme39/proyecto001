---
version: alpha
name: Ingrid Rosas — Design System
description: Sistema de diseño de la marca Ingrid Rosas (portfolio de diseño). Estética moderna, dinámica y creativa construida sobre azul primario y naranja de acento, con profundidad por capas, sombras suaves y espacio en blanco generoso.
colors:
  primary: "#0C42BC" # azul de marca: CTAs, acentos, títulos, identidad
  secondary: "#FF7900" # naranja de acento
  tertiary: "#0F0F43" # azul oscuro: enlaces e interactivos secundarios
  button-orange: "#F19A3B" # naranja de botón: botones secundarios y fantasma
  surface: "#FCFCFC" # fondo base, casi blanco
  surface-bright: "#FFFFFF" # blanco puro para máximo contraste
  text-primary: "#0F0F43" # REVISAR: color de texto del cuerpo, inferido
  primary-tint: "#E8EDFB" # REVISAR: azul en tonalidad suave para chips, inferido
  error: "#F19A3B" # REVISAR: variante naranja para errores, inferido
  border: "#E0E0E0" # REVISAR: gris claro para bordes de campos, inferido
typography:
  display:
    fontFamily: Beautiful Freak
    fontSize: 40px
    fontWeight: 700
    lineHeight: 48px
  h1:
    fontFamily: Beautiful Freak
    fontSize: clamp(32px, 5vw, 56px)
    fontWeight: 700
  h2:
    fontFamily: Beautiful Freak
    fontSize: clamp(28px, 4vw, 40px)
    fontWeight: 700
  h3:
    fontFamily: Beautiful Freak
    fontSize: 20px
    fontWeight: 700
  body-lg:
    fontFamily: Helvetica Neue
    fontSize: 20px
    fontWeight: 300
    lineHeight: 30px
  body-md:
    fontFamily: Helvetica Neue
    fontSize: 16px
    fontWeight: 300
  list:
    fontFamily: Helvetica Neue
    fontSize: 16px
    fontWeight: 300
  label:
    fontFamily: Helvetica Neue
    fontSize: 16px
    fontWeight: 800
  button:
    fontFamily: Helvetica Neue
    fontSize: 19px
    fontWeight: 700
  nav:
    fontFamily: Helvetica Neue
    fontSize: 18px
    fontWeight: 400
  link:
    fontFamily: Helvetica Neue
    fontSize: 20px
    fontWeight: 300
  chip:
    fontFamily: Helvetica Neue
    fontSize: 14px
    fontWeight: 700
rounded:
  md: 8px
  lg: 12px
  xl: 16px
  2xl: 24px
  pill: 50px
  full: 50%
spacing:
  xs: 4px
  sm: 8px
  md: 12px
  lg: 16px
  xl: 24px
  2xl: 32px
  3xl: 40px
  4xl: 48px
  5xl: 92px
  6xl: 136px
  max-width: 1440px
  columns-desktop: 12
  columns-tablet: 8
  columns-mobile: 1
  margin-tablet: 48px
  margin-mobile: 12px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.surface-bright}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "12px 24px"
  button-primary-hover:
    shadow: "0 4px 12px rgba(0, 0, 0, 0.12)"
    transform: "scale(1.01)"
  button-primary-pressed:
    transform: "scale(0.99)"
    shadow: "none"
  button-secondary:
    backgroundColor: "{colors.button-orange}"
    textColor: "{colors.tertiary}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "12px 24px"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.tertiary}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
  button-icon:
    size: "40x40px"
    rounded: "{rounded.full}"
    backgroundColor: "{colors.primary}"
  card:
    backgroundColor: "{colors.surface-bright}"
    rounded: "{rounded.lg}"
    padding: "24px 32px"
    shadow: "0 2px 4px rgba(0, 0, 0, 0.04)"
  card-hover:
    shadow: "0 2px 4px rgba(0, 0, 0, 0.08)"
    transform: "scale(1.01)"
  input:
    backgroundColor: "{colors.surface-bright}"
    textColor: "{colors.tertiary}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    border: "1px solid #E0E0E0" # REVISAR
    padding: "12px 16px"
  input-focus:
    border: "1px solid {colors.primary}"
  nav-link:
    textColor: "{colors.tertiary}"
    typography: "{typography.nav}"
  link:
    textColor: "{colors.primary}"
    typography: "{typography.link}"
  social-icon:
    size: "40x40px"
    rounded: "{rounded.full}"
    backgroundColor: "{colors.surface}"
    textColor: "{colors.tertiary}"
  social-icon-hover:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.surface-bright}"
  chip:
    rounded: "{rounded.pill}"
    typography: "{typography.chip}"
    backgroundColor: "{colors.surface}"
  avatar:
    rounded: "{rounded.full}"
  avatar-rounded:
    rounded: "{rounded.2xl}"
---

# Ingrid Rosas — Sistema de Diseño

## Overview

La marca encarna una estética moderna, dinámica y centrada en la creatividad, que tiende un puente entre la experimentación y la calidad del trabajo. Se apoya en naranja vibrante y azul profundo, y transmite confianza, creatividad e imaginación. Prioriza la claridad y la legibilidad con una filosofía minimalista: layouts limpios, espacio en blanco y tipografía con propósito. Está pensada para presentar la creatividad de la autora como diseñadora, respetando el tiempo y la carga cognitiva del usuario. En una frase: un acento de imaginación y experimentación, pero sin caer en lo alocado y sin propósito.

## Colors

La paleta se construye sobre azul y naranja de marca y una base de neutros de alto contraste.

- **Primary (#0C42BC):** azul de marca. Se usa para botones de acción (CTA), acentos, títulos e identidad de marca.
- **Secondary (#FF7900):** naranja vibrante. Da acentos a la página.
- **Tertiary (#0F0F43):** azul oscuro. Color de enlaces y elementos interactivos secundarios.
- **Button-orange (#F19A3B):** naranja de botón. Fondo de botones secundarios y fantasma.
- **Surface (#FCFCFC):** gris muy claro. Fondo base, casi blanco.
- **Surface-bright (#FFFFFF):** blanco puro para máximo contraste.
- **Text-primary (#0F0F43):** `REVISAR` — color del cuerpo de texto, inferido de {colors.tertiary}.
- **Primary-tint (#E8EDFB):** `REVISAR` — tonalidad suave de azul para chips y etiquetas, inferida.
- **Error (#F19A3B):** `REVISAR` — variante naranja para estados de error, inferida del doc.
- **Border (#E0E0E0):** `REVISAR` — gris claro para bordes de campos, inferido.

Azul y naranja nunca se usan con la misma intensidad y protagonismo dentro de un mismo elemento: uno domina y el otro funciona como acento. Los fondos blancos y gris claro se usan para que el azul y el naranja tengan mayor protagonismo.

### Design Tokens

Ver bloque YAML `colors`. Referencias: {colors.primary}, {colors.secondary}, {colors.tertiary}, {colors.button-orange}, {colors.surface}, {colors.surface-bright}.

## Typography

Se usan dos familias con roles claros:

- **Beautiful Freak Bold:** fuente display para títulos e identidad. Se entrega localmente como `fonts/Beautiful-Freak-Bold.woff` con peso 700.
- **Helvetica Neue:** fuente principal para cuerpo, navegación y contenido general. Disponible en pesos 300 (Light), 400 (Regular), 700 (Bold) y 800 (Heavy). Se entrega localmente como `fonts/helvetica/HelveticaNeueLTStd-*.woff`.
- **Helvetica:** fuente complementaria en pesos 400 (Roman) y 700 (Bold).

### Jerarquía de pesos tipográficos

| Peso | Uso | Elementos |
|------|-----|-----------|
| 800 (Heavy) | Eyebrows, fechas | `.eyebrow`, `.timeline-item .date` |
| 700 (Bold) | Títulos, marcas, labels | `h1-h4`, `.brand-name`, `.chip`, `.btn`, `.tool-logo span` |
| 500 (Medium) | Botones | `.btn` |
| 400 (Regular) | Navegación, habilidades | `.nav-links a`, `.skill-item span`, `.contact-btn` |
| 300 (Light) | Cuerpo de texto | `body`, `.section-head p`, `.timeline-item p`, `.interest-body p` |

### Tamaños

- **Display:** Beautiful Freak Bold a 40px con interlineado de 48px.
- **Título 1 (h1):** Beautiful Freak Bold a clamp(32px, 5vw, 56px), peso 700.
- **Título 2 (h2):** Beautiful Freak Bold a clamp(28px, 4vw, 40px), peso 700.
- **Título 3 (h3):** Beautiful Freak Bold a 20px, peso 700.
- **Cuerpo de texto:** Helvetica Neue Light a 20px con interlineado de 30px.
- **Ítems de lista:** Helvetica Neue Light a 16px.
- **Texto pequeño:** Helvetica Neue Regular a 16px.
- **Etiquetas de botones:** Helvetica Neue Bold a 19px.
- **Chips:** Helvetica Neue Bold a 14px.
- **Navegación:** Helvetica Neue Regular a 18px.
- **Habilidades:** Helvetica Neue Regular a 16px.

La jerarquía se logra con tamaño, peso y color. El cuerpo nunca baja de 16px. Helvetica Neue Heavy (800) se reserva para eyebrows y fechas. Beautiful Freak se usa únicamente para títulos y display.

### Design Tokens

Ver bloque YAML `typography` (`display`, `h1`, `h2`, `h3`, `body-lg`, `body-md`, `list`, `label`, `button`, `nav`, `link`, `chip`).

## Layout

El espaciado se basa en una unidad de 8px. La escala va de 4px (microespaciado) a 8, 12, 16, 24, 32, 40, 48, 92 y 136px. Los botones y campos usan 12–16px de espacio interno; las tarjetas 12–24px; y las secciones grandes se separan por 48–92px verticales.

El ancho máximo del contenido es 1440px. En escritorio se usa una rejilla de 12 columnas; en tableta, 8 columnas con márgenes de 48px; en móvil, una sola columna con márgenes de 12–16px.

El espacio en blanco es generoso e intencional: el contenido nunca va apretado y las secciones se separan por al menos 92px para crear zonas visuales claras.

### Design Tokens

Ver bloque YAML `spacing` (`xs`–`6xl`, `max-width`, `columns-*`, `margin-*`).

## Elevation & Depth

El diseño cuenta con profundidad visual en toda la página, creando una sensación de capas y elementos flotantes. Se usan sombras suaves, transparencias, desenfoques y superposiciones para separar los elementos del fondo sin perder una estética limpia y moderna.

Niveles de elevación:
- **Relieve mínimo:** navegación, campos y tarjetas en reposo (sombra casi imperceptible).
- **Elevación sutil:** `0 2px 4px` con opacidad 0.08, para el hover de las tarjetas.
- **Elevación media:** `0 4px 12px` con opacidad 0.12, para tarjetas destacadas, modales y popovers (y hover de botones).
- **Elevación alta:** `0 8px 24px` con opacidad 0.16, para botones y elementos flotantes.
- **Velo modal:** negro al 0.5 con desenfoque, para hacer retroceder el contenido de fondo cuando aparece un modal.

Las tarjetas permanecen ligeramente elevadas y, al pasar el cursor, aumentan sutilmente su escala y sombra, dando la sensación de acercarse al usuario. Algunos elementos se superponen entre secciones y se desplazan a diferentes velocidades durante el scroll para generar un ligero efecto parallax. La intención es que la página se perciba como un espacio digital compuesto por distintos planos que se acercan, se alejan y reaccionan a la navegación, manteniendo siempre una apariencia limpia, dinámica y contemporánea.

## Shapes

Las formas combinan una estética limpia y moderna con pequeños gestos experimentales, evitando que todos los elementos se perciban demasiado rígidos o uniformes.

- **Base:** redondeo de 8px, suficiente para suavizar la interfaz sin perder carácter gráfico.
- **Tarjetas destacadas, imágenes y elementos flotantes:** radios de 12px a 16px.
- **Elementos orgánicos o cercanos:** hasta 24px.
- **Círculos perfectos (50%):** botones de ícono, indicadores, elementos decorativos y algunos recursos gráficos.
- **Botones principales:** forma tipo píldora (50px), generando contraste con las composiciones más estructuradas.

Como recurso de identidad se usa un robot, que puede aparecer completo o fragmentado en diferentes partes de la interfaz. Algunas de sus formas pueden sobresalir de tarjetas, esconderse detrás de textos o atravesar ligeramente los límites de una sección, reforzando la sensación de capas, profundidad e imaginación. También se incorporan ocasionalmente formas geométricas, líneas, círculos y bloques de color azul y naranja como recursos compositivos; estos nunca son únicamente decorativos: ayudan a dirigir la mirada, separar información o destacar partes importantes del contenido.

### Design Tokens

Ver bloque YAML `rounded` (`md`, `lg`, `xl`, `2xl`, `pill`, `full`).

## Components

### Botones

- **Principal:** fondo {colors.primary}, texto {colors.surface-bright} en Google Sans Flex Regular a ~19px. Esquinas tipo píldora (50px) y espacio interno de 12px verticales por 24px horizontales. En hover se eleva ligeramente, aumenta mínimamente su escala y genera una sombra suave de `0 4px 12px` con opacidad 0.12. Al presionarlo vuelve hacia el plano de la página y reduce ligeramente su escala.
- **Secundario:** fondo {colors.button-orange} con texto en {colors.tertiary} o blanco según contraste. Misma estructura redondeada, con menor peso visual que el CTA principal.
- **Ícono:** circulares, mínimo 40×40px, fondo azul o gris muy claro. En hover pueden desplazarse hacia arriba, cambiar de color o rotar algunos grados.
- **Fantasma:** sin fondo, texto en {colors.tertiary}, pueden incorporar una flecha o pequeño elemento naranja. En hover aparece una línea, desplazamiento horizontal o cambio hacia {colors.secondary}.

### Tarjetas y contenedores

Fondos {colors.surface-bright} o {colors.surface}, esquinas de 8px a 16px y espacios internos de 24px a 32px. En reposo tienen un relieve mínimo. En hover se elevan, aumentan su sombra y pueden crecer entre 1% y 2%. Algunas tarjetas se superponen parcialmente con imágenes, títulos, formas geométricas o elementos del robot; esta ruptura controlada de la cuadrícula aporta dinamismo, pero siempre mantiene clara la lectura del contenido. Las tarjetas más importantes pueden usar una línea, bloque o pequeña superficie naranja como acento, mientras que el azul funciona como color estructural.

### Hero

Primer momento de impacto visual. Fondo claro ({colors.surface} o {colors.surface-bright}), tipografía de gran escala, elementos del robot, bloques de color y distintos niveles de profundidad. El contenido mantiene suficiente espacio en blanco, pero algunos elementos pueden salirse ligeramente de la cuadrícula, superponerse o desplazarse durante el scroll. El título principal puede usar Beautiful Freak Bold como elemento expresivo, combinado con Google Sans Flex Extra Bold para equilibrar personalidad y legibilidad.

### Campos y formularios

Campos con fondo blanco, texto en Google Sans Flex Regular a 18–20px y espacio interno de 12px por 16px. Esquinas de 8px y borde sutil en gris claro ({colors.border} `REVISAR`). Al recibir foco, el borde cambia a {colors.primary} y aparece un halo o sombra suave. Para errores se usan variaciones del naranja sin depender únicamente del color para comunicar el estado. Las etiquetas usan Google Sans Flex Extra Bold a 16px.

### Navegación y enlaces

Navegación en Google Sans Flex Regular a 18–20px en {colors.tertiary}. El elemento activo puede incorporar una línea inferior, punto o pequeño detalle en {colors.secondary}. En hover, los enlaces pueden cambiar hacia {colors.primary} o naranja y presentar una microanimación horizontal o un subrayado progresivo. Los enlaces integrados en el contenido usan {colors.primary} para distinguirse del texto general.

### Íconos sociales

Botones circulares de 40×40px, inicialmente con fondos claros e íconos en {colors.tertiary}. En hover pueden transformarse a {colors.primary} con ícono blanco, elevarse ligeramente y generar una sombra sutil. Algunos incorporan un pequeño detalle naranja como recurso de identidad.

### Etiquetas y chips

Formas tipo píldora con fondo en tonalidades suaves de azul. Texto en Helvetica Neue Bold a 14px.

### Avatar

La fotografía de perfil se presenta en forma circular o en contenedor redondeado de 16px a 24px. Puede incorporar detrás una segunda capa desplazada en naranja o azul, generando profundidad y evitando que la foto parezca simplemente colocada.

### Tarjetas de proyectos

Tarjetas visuales donde la imagen tiene mayor protagonismo. Título en Beautiful Freak Bold, descripción breve en Helvetica Neue Light y etiquetas (chips) que identifican disciplinas. En hover, la imagen aumenta ligeramente de escala mientras la tarjeta se eleva. Algunas tarjetas incluyen carrusel automático (Ilustración, Editorial) o video con poster (Gráficos en movimiento). Al hacer clic en cualquier imagen se abre un lightbox con vista amplia; los carruseles incluyen flechas de navegación.

### Carrusel

Componente de imágenes con transición automática cada 3 segundos. Las imágenes se ocultan con `visibility:hidden` y se muestran con fade. El carrusel se imprime en el lightbox con flechas de navegación izquierda/derecha, también navegables con las teclas del teclado (← →).

### Lightbox

Modal a pantalla completa con fondo oscuro (`rgba(0,0,0,.9)`). Muestra la imagen o video del proyecto en tamaño amplio. Incluye botón de cerrar (×) y se cierra con Escape o clic fuera del contenido. Los carruseles muestran flechas de navegación. El scroll del body se bloquea mientras está abierto.

### Educación y experiencia

Tarjetas o bloques organizados verticalmente con línea temporal. Una línea degradada (azul a naranja) funciona como eje visual conectando etapas. El título usa Beautiful Freak Bold, las fechas Helvetica Neue Heavy (800) en naranja y las descripciones Helvetica Neue Light. Los elementos aparecen progresivamente durante el scroll.

### Design Tokens

Ver bloque YAML `components` (`button-primary*`, `button-secondary`, `button-ghost`, `button-icon`, `card*`, `input*`, `nav-link`, `link`, `social-icon*`, `chip`, `avatar*`).

## Do's and Don'ts

**Sí**
- Usa azul {colors.primary} como color principal de interacción e identidad y naranja {colors.secondary} como acento visual.
- Mantén Google Sans Flex como familia principal para garantizar legibilidad y usa Beautiful Freak Bold estratégicamente para aportar personalidad.
- Mantén un tamaño de cuerpo cercano a 20px en escritorio y nunca menor a 16px.
- Usa espacios amplios de 48–92px o más entre secciones para que cada bloque tenga suficiente presencia.
- Genera profundidad mediante capas, sombras suaves, superposiciones, escalas y movimiento, no mediante efectos excesivos.
- Permite que algunos elementos gráficos rompan intencionalmente la cuadrícula para reforzar el carácter creativo de la página.
- Usa el robot y sus formas como un recurso narrativo y visual recurrente, no únicamente como logotipo.
- Mantén las animaciones rápidas, suaves y funcionales. Cada movimiento debe comunicar interacción, jerarquía o profundidad.
- Usa los fondos blancos y gris claro para que el azul y el naranja tengan mayor protagonismo.
- Mantén una jerarquía clara incluso cuando la composición experimente con posiciones, escalas y capas.

**No**
- No uses azul y naranja con la misma intensidad y protagonismo dentro de un mismo elemento; uno debe dominar y el otro funcionar como acento.
- No conviertas todas las tarjetas y componentes en elementos completamente planos; la profundidad forma parte de la personalidad de la página.
- No uses sombras superiores a `0 8px 24px` con opacidad 0.16, para evitar una apariencia pesada.
- No uses Beautiful Freak Bold en textos largos, formularios o información que requiera lectura continua.
- No uses tipografías adicionales como PT Sans, Raleway u otras familias que rompan el sistema tipográfico establecido.
- No reduzcas los botones interactivos a tamaños que dificulten su identificación o interacción.
- No uses movimiento, parallax o animaciones únicamente como decoración; deben responder a una intención visual.
- No llenes todos los espacios vacíos. El espacio en blanco también forma parte de la composición.
- No abuses de bordes, sombras y degradados simultáneamente en un mismo componente.
- No permitas que la experimentación comprometa la legibilidad, navegación o comprensión del contenido.
- No busques que todos los elementos sean perfectamente simétricos: la página puede usar asimetrías controladas, superposiciones y cambios de escala para transmitir creatividad sin perder estructura.

## Review Notes

Valores actualizados:
1. `colors.text-primary` → #0F0F43
2. `colors.primary-tint` → #E8EDFB
3. `colors.error` → #F19A3B
4. `colors.border` → #E0E0E0
5. Tipografía unificada: Beautiful Freak para títulos, Helvetica Neue para cuerpo y navegación.
6. Jerarquía de pesos: 800 (eyebrows), 700 (títulos), 400 (navegación), 300 (cuerpo).
7. Agregado: Componente Lightbox para vista amplia de proyectos.
8. Agregado: Componente Carrusel con transición automática y flechas de navegación.
9. Sección Mi Trabajo: 6 tarjetas (Ilustración, Identidad de marca, Gráficos en movimiento, Modelado, Campañas, Editorial).
