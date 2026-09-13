# Casa Núcleo · Concepto de la página web

Documento de trabajo para pulir la idea antes de construir.

Fuentes:

- Flipbook "Casa Núcleo · Ideas que habitan" (6 páginas, 11 sep 2026). Ver `docs/referencia/flipbook-0*.jpg`.
- Web v1 ya construida (artefacto `21aca694`). Copia en `docs/referencia/web-v1/` con sus logotipos. El video de portada (`portada.mp4`, 10 MB) no se copió al repositorio; sigue en el artefacto.

---

## 1. Punto de partida: hay dos versiones de la idea y no dicen lo mismo

| | Web v1 | Flipbook (más reciente) |
|---|---|---|
| Titular | "Diseñamos tu marca. Y el negocio que la sostiene." | "Consultoría de desarrollo de negocios" |
| Cómo se organiza la oferta | **Por proceso**: cinco pasos en orden (Cliente Invisible → Manual de Cimientos → Marca con Alma → Sitio a la Medida → Manual de Crecimiento), cada uno cotizado por separado | **Por tipo de cliente**: tres programas (Impulsa: por abrir · Eleva: con trayectoria · A la medida: cadenas y sucursales) |
| Entregable | Un documento por paso (bitácora, dos manuales, identidad, sitio) | **Un solo entregable**: el Manual Núcleo, ocho capítulos |
| Puerta de entrada | Paso I, Cliente Invisible, que se cotiza | **Diagnóstico Núcleo, sin costo**: "revisamos tu negocio como lo haría un cliente" |
| Acción principal | "Agendar una llamada" / "Quiero que entren a mi negocio" | (implícita) pedir el diagnóstico |
| Lema | "Ideas que habitan" en la barra, pero "Ideas con esencia" en el pie | "Ideas que habitan" en todas las páginas |
| Criterio | Tres columnas: no prometemos / sí garantizamos / siempre por escrito | Dos frases, mismo fondo |
| Equipo | Dos socias, con nombres pendientes | No aparece |
| Portafolio | Tres casos "en preparación / próximamente" | No aparece |
| Sección "El sitio" | Demos interactivas de la web como servicio | No aparece; la web es un punto dentro de los programas |

**Lectura:** el flipbook es la versión pulida del negocio. Está fechado dos días atrás, es lo que va a estar en manos de clientes, y simplifica la oferta a algo que el dueño de un negocio entiende en diez segundos ("¿voy a abrir o ya tengo historia?"). La web v1 tiene mucho valor, pero cuenta una oferta anterior. Si web y flipbook dicen cosas distintas, se pierde confianza justo en el negocio cuyo argumento es "todo queda por escrito".

**Decisión propuesta:** la web adopta la arquitectura del flipbook (programas + Manual Núcleo + Diagnóstico sin costo) y conserva de la v1 todo lo que no contradice eso: sistema visual, movimiento, secciones de equipo y criterio, y el lenguaje del "cliente invisible", que es la mejor explicación posible de qué es el Diagnóstico Núcleo.

---

## 2. Qué se conserva de la web v1 (mucho)

- **El sistema visual completo.** Paleta (`--crema`, `--beige`, `--olivo`, `--vino`, `--oro`, `--rosa`), Cormorant Garamond + Montserrat, los cinco temas de sección, las etiquetas en mayúsculas espaciadas, el rombo ✦, la textura de papel. Ya es coherente con el flipbook.
- **Los logotipos** en cuatro versiones con fondo transparente (oro y crema, completo e isotipo). Resuelto el pendiente del logo.
- **La sección "Qué hacemos"** con el párrafo del mostrador: "La mayoría de los estudios empiezan por el logotipo. Nosotras empezamos por el mostrador, por el teléfono y por el buzón de tus redes". Es el mejor texto de toda la v1.
- **La sección "Somos"** (dos socias con responsabilidades definidas por escrito). Resuelve el pendiente de "quién está detrás". Faltan nombres y fotos.
- **La sección "Nuestro criterio"** en tres columnas. Es más completa que la del flipbook y dice lo mismo.
- **Los tres principios de "Los documentos"**: escritos para quien no estuvo en las juntas · ninguno se parece a otro · tuyos al cerrar, sin letras chiquitas. Pasan a la sección del Manual Núcleo.
- **La caja "Cómo empieza"** con sus cuatro condiciones (empiezas por donde quieras, cada paso se cotiza aparte, alcance y precio por escrito antes de arrancar, sin permanencia). Se reescribe para el Diagnóstico.
- **La mecánica**: menú fijo y panel móvil, revelado al hacer scroll, barra de avance, botón "Reducir movimiento", respeto a `prefers-reduced-motion`. Todo bien hecho.
- **El campo "Etapa del negocio"** en el formulario.

## 3. Qué cambia

| Elemento de la v1 | Cambio | Por qué |
|---|---|---|
| Titular "Diseñamos tu marca…" | Nuevo titular alineado al flipbook. Propuesta: **"Impulsamos negocios nuevos. Elevamos los que ya tienen historia."** con "Más negocios bien hechos." como remate | El flipbook vende desarrollo de negocios; la v1 abre vendiendo diseño |
| Botón "Agendar una llamada" | **"Pide tu Diagnóstico Núcleo · sin costo"** en portada, en la caja "Cómo empieza" y en contacto | Gratis y concreto convierte más que "llamada" |
| Cinco pasos | Se reemplazan por **tres programas** con los puntos del flipbook. El orden y la lógica de "primero corregir, luego vestir" sobreviven como texto dentro de "Qué hacemos" | Es la oferta vigente |
| "Cliente Invisible" como Paso I | Se convierte en la **descripción del Diagnóstico Núcleo**: "Entramos a tu negocio como cualquier cliente, sin avisar: escribimos a tus redes un sábado, preguntamos precios, visitamos el local. Te decimos qué encontramos. Sin costo." | Es el mismo servicio, ahora gratis; el texto de la v1 es excelente |
| "Los documentos" (bitácora, manuales sueltos) | **"El Manual Núcleo"**: los ocho capítulos del flipbook + la ficha de entrega de la v1 (editable y PDF, plantillas, sesión acompañada, propiedad del negocio) + los tres principios | Un solo entregable, más fácil de vender y de explicar |
| Sección "El sitio" con demos | **Se elimina.** La propia página demuestra el oficio. Si se quiere conservar algo, una línea en el pie: "Este sitio lo hicimos nosotras, como los de nuestros clientes" | En el flipbook la web es un punto dentro de los programas, no un servicio estrella. Además pesa y distrae de la única acción |
| Portafolio con "próximamente" | **Se retira hasta tener dos o tres casos reales.** Si Univox es real y autoriza, se deja solo ese | Tres tarjetas vacías restan más de lo que suman |
| Formulario por `mailto:` | **Formspree (o Netlify Forms) + botón de WhatsApp** con mensaje prellenado | `mailto:` falla en muchos celulares y no deja registro |
| Video de portada de 10 MB | **Imagen fija de portada en celular; video solo en escritorio** y comprimido a 2 MB o menos (1080p, sin audio, 8 a 10 segundos) | Diseño móvil primero: el dueño del negocio llega desde WhatsApp con datos móviles |
| Lema del pie "Ideas con esencia" | "Ideas que habitan" | Un solo lema |
| Datos de contacto de muestra | Reales antes de publicar | La v1 ya lo advierte en una nota |

---

## 4. Estructura propuesta (v2)

Una sola página larga, diseñada primero para celular. Nueve secciones. Es una reescritura de contenido sobre el código de la v1, no un sitio nuevo.

| # | Sección | Tema visual | Qué contiene |
|---|---|---|---|
| 0 | Barra | crema | Isotipo oro + anclas: Qué hacemos · Programas · Manual · Diagnóstico · Contacto. Botón "Diagnóstico sin costo" |
| 1 | **Portada** | crema + figura beige | "Consultoría de desarrollo de negocios" · titular nuevo · las tres ciudades · botón principal · enlace "Ver los programas" |
| 2 | **Qué hacemos** | olivo | Párrafo del flipbook ("Impulsamos negocios nuevos y elevamos los que ya tienen historia. Escribimos contigo cómo decide, cómo opera y cómo crece tu negocio, y te lo entregamos por escrito.") + el párrafo del mostrador de la v1 + cita "La belleza también es una estrategia." |
| — | Cinta | noche | Frases de marca del flipbook rotando: Un futuro más humano · Ideas hoy, realidades mañana · Negocios con alma · Marcas que evolucionan, personas que trascienden |
| 3 | **¿Cuál es tu caso?** | beige | Tres rutas (el componente `.rutas` de la v1): **Impulsa** · negocios nuevos o por abrir · 5 puntos. **Eleva** · negocios con trayectoria · 5 puntos. **A la medida** · grupos, cadenas y sucursales · 5 puntos. La del medio en vino, como en la v1 |
| 4 | **El Manual Núcleo** | vino | "Lo que se queda contigo". Ficha de entrega a la izquierda (el `.tomo` de la v1). A la derecha los ocho capítulos numerados: diagnóstico y mercado · cliente y propuesta · portafolio y precios · modelo operativo · identidad de marca · canales de venta · plan comercial · indicadores. Debajo, los tres principios. Cierre: *Todo queda por escrito* |
| 5 | **Por aquí se empieza** | noche (la caja `.entrada`) | **Diagnóstico Núcleo · sin costo.** Texto del cliente invisible. Tres pasos: nos escribes → entramos a tu negocio como clientes → te decimos qué encontramos y, si hay ruta, cuál programa te conviene. Condiciones: sin costo, sin compromiso, "si no sale una ruta que te convenga, te lo decimos y hasta ahí llegamos". Botón |
| 6 | **Somos** | olivo | Dos socias, con nombres, fotos y qué responde cada una (reparto por programa o por área: negocio / marca) |
| 7 | **Nuestro criterio** | beige | Las tres columnas de la v1 tal cual |
| 8 | **Contacto** | noche | Formulario: nombre, negocio, ciudad, etapa (Todavía no abre · Abrió hace poco · Con años de operación · Varias sucursales), WhatsApp, comentario. Botón de WhatsApp al lado. Datos reales |
| 9 | Pie | noche | Logo crema, "Ideas que habitan", enlaces, ciudades, "Más negocios bien hechos.", botón de reducir movimiento |

Las cuatro opciones de "etapa" se mapean a los programas: las dos primeras a Impulsa, la tercera a Eleva, la cuarta a A la medida. Casa Núcleo sabe qué programa aplica antes de la primera conversación.

---

## 5. Dirección visual

Se toma de la v1 sin cambios de fondo. Únicos ajustes:

- **Portada en celular:** imagen fija (una hoja vino sobre crema, en la línea del flipbook) en lugar de video. En escritorio, video comprimido.
- **Arcos.** El flipbook usa el arco de piedra con filo dorado como motivo. La v1 usa una figura orgánica con filo dorado en la portada. Son compatibles; se puede llevar el arco a las tarjetas de programas y a las fotos de las socias (recorte en arco).
- **Peso.** Objetivo: página completa por debajo de 1.5 MB en celular sin contar el video de escritorio. Los cuatro PNG de logotipo suman 2.3 MB; se convierten a WebP o SVG (el isotipo en oro de 748 KB solo se usa a 42 px de alto).

## 6. Tono

- De tú, en femenino plural cuando hablan de sí mismas ("nosotras", "las socias"), como la v1.
- Frases cortas, sin jerga. El flipbook y la v1 ya lo hacen bien; no mezclar con "estrategia digital", "KPIs", "branding".
- Nada de promesas numéricas. El criterio va literal.

## 7. Recomendación técnica

| Decisión | Recomendación |
|---|---|
| Base de código | La v1: HTML + CSS + JS sin framework. Se edita contenido y se quitan dos secciones |
| Hospedaje | GitHub Pages desde este repositorio, con dominio propio |
| Formulario | Formspree (gratis hasta 50 envíos al mes) + enlace `wa.me` con mensaje prellenado |
| Video | Solo escritorio, `preload="none"`, imagen de portada (`poster`) en todos los casos |
| SEO local | Título "Casa Núcleo · Consultoría de desarrollo de negocios en Monterrey", datos estructurados `LocalBusiness` con las tres ciudades, ficha de Google Business Profile |
| Medición | Solo dos eventos: envío de formulario y clic en WhatsApp |

---

## 8. Decisiones abiertas

Ya resueltas por la v1: logotipos (existen), equipo (dos socias), dominio y correo (`casanucleo.mx` y `hola@casanucleo.mx` aparecen en la v1; confirmar que son reales).

Siguen abiertas:

1. **¿Se adopta la arquitectura del flipbook?** Es la decisión que define todo lo demás. Recomendación: sí.
2. **Nombres y fotos de las socias**, y cómo se reparten (por programa o por área).
3. **WhatsApp e Instagram reales.**
4. **Univox:** ¿es un caso real que se puede mostrar? Si no, el portafolio se retira.
5. **Precios:** no se muestran; "la propuesta llega por escrito después del diagnóstico". Confirmar.
6. **Muestra del Manual Núcleo:** una o dos páginas reales o de ejemplo para la sección 4. Recomendación: sí.
7. **¿Se conserva "Sitio a la Medida" como servicio visible?** Recomendación: no como sección; sí como punto dentro de Impulsa ("presencia inicial") y Eleva ("presencia digital"), que es donde el flipbook lo pone.

## 9. Siguientes pasos

1. Confirmar la decisión 1 y contestar el resto (con los valores por defecto si no hay objeción).
2. Reescribir la v1 sobre este repositorio con la estructura de la sección 4: contenido nuevo, mismo sistema visual.
3. Publicar en GitHub Pages con dominio, formulario y WhatsApp.
