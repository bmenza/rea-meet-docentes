# Clases virtuales con Google Meet

**Recurso Educativo Abierto (REA) para docentes de DGETP y DGES de Uruguay.**
Guía de una sola página sobre las funcionalidades y ventajas de Google Meet para dictar clases virtuales: primera clase paso a paso, presentar pantalla, pizarra, participación del grupo, salas para grupos, seguridad y accesibilidad.

- **Autor:** Bruno Menza
- **Licencia:** [Creative Commons Atribución 4.0 Internacional (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.es)
- **Última revisión:** 31 de octubre de 2026

## Qué podés hacer con este recurso

Podés copiarlo, adaptarlo, traducirlo y redistribuirlo (incluido `style.css`), incluso con fines comerciales, siempre que cites la autoría e indiques si hiciste cambios.

Cita sugerida (APA 7.ª edición):

> Menza, B. (2026). *Clases virtuales con Google Meet: guía para docentes de DGETP y DGES* [Recurso Educativo Abierto]. Licencia CC BY 4.0.

## Contenido

| Sección | De qué trata |
|---|---|
| Ventajas | Por qué usar Meet en el aula |
| Primera clase | Crear, programar y compartir una reunión |
| Funciones | Presentar pantalla, participación, gestión, accesibilidad y conectividad |
| Pizarra | Alternativas ahora que Jamboard ya no existe |
| Trabajo en grupos | Salas para grupos pequeños |
| Seguridad | Buenas prácticas y lista previa a la clase |
| Referencias | Bibliografía en APA 7.ª edición |

## Estructura del repositorio

```
.
├── index.html   # Estructura y contenido de la página (con un pequeño script para tema y compartir)
├── style.css    # Estilos: paleta accesible, diseño responsive, impresión
├── img/         # Imágenes del recurso (portada, ventajas, pantalla, seguridad)
├── README.md    # Este archivo
└── LICENSE      # Texto de la licencia CC BY 4.0 (agregarlo, ver más abajo)
```

No requiere instalación ni compilación. `index.html`, `style.css` y la carpeta `img/` deben estar juntos. Las únicas dependencias externas son las tipografías de Google Fonts (*Atkinson Hyperlegible* y *Bricolage Grotesque*); si no cargan, se usan las fuentes del sistema.

## Publicar en GitHub Pages

1. Creá un repositorio público, por ejemplo `meet-docentes`.
2. Subí `index.html`, `style.css`, la carpeta `img/`, `README.md` y `LICENSE`.
3. En **Settings → Pages**, elegí la rama `main` y la carpeta `/ (root)`.
4. La página quedará en `https://TU-USUARIO.github.io/meet-docentes/`.
5. Descargá el texto legal de CC BY 4.0 desde [creativecommons.org](https://creativecommons.org/licenses/by/4.0/legalcode.es) y guardalo como `LICENSE`.

Para probar en tu computadora basta con abrir `index.html` en el navegador.

## Accesibilidad

El diseño sigue los requisitos técnicos de accesibilidad digital del Estado uruguayo (Decreto 406/022, AGESIC), que remiten a las pautas WCAG 2.1:

- Niveles **A y AA**.
- Criterios AAA de **contraste aumentado (1.4.6)** y **presentación visual (1.4.8)**.

Medidas aplicadas:

- **Contraste:** el texto cumple una relación mínima de 7:1 en modo claro y oscuro. Bordes, íconos y componentes de interfaz cumplen al menos 3:1.
- **Presentación del texto:** interlineado de 1,6, párrafos de hasta 70 caracteres por línea, sin texto justificado y con separación amplia entre párrafos.
- **Teclado y foco:** enlace para saltar al contenido, foco visible y áreas táctiles de al menos 44 px.
- **Adaptación:** diseño responsive sin desplazamiento horizontal, incluso con zoom al 200 % y en pantallas de 320 px. La tabla de pizarras se convierte en tarjetas en pantallas pequeñas.
- **Color:** la información no depende solo del color, y los enlaces están siempre subrayados.
- **Preferencias del usuario:** modo claro y oscuro (automático o manual), respeto de `prefers-reduced-motion` y estilos de impresión.
- **Ilustraciones:** SVG con título y descripción para lectores de pantalla.

> Este sitio **no cuenta con una auditoría externa**. Se recomienda verificarlo con herramientas como axe, WAVE o Colour Contrast Analyser, y con lector de pantalla, antes de difundirlo.

### Paleta de colores

| Uso | Modo claro | Modo oscuro |
|---|---|---|
| Texto principal | `#0B1F24` sobre `#FFFFFF` (16,99:1) | `#F1F8F9` sobre `#0A181C` (16,84:1) |
| Texto secundario | `#2F4851` sobre `#FFFFFF` (9,69:1) | `#BFD3D7` sobre `#0A181C` (11,65:1) |
| Color de marca y enlaces | `#00534F` sobre `#FFFFFF` (8,94:1) | `#8EE6DF` sobre `#0A181C` (12,53:1) |
| Acento (bordes) | `#8A5200` (6,39:1) | `#FFC457` (11,45:1) |
| Bordes de interfaz | `#6B8890` (3,78:1) | `#7C9BA2` (6,09:1) |

## Cómo adaptar el recurso

- **Imágenes:** están en `img/` (`portada.jpg`, `ventajas.jpg`, `pantalla.jpg`, `seguridad.jpg`) y tienen texto alternativo en el HTML. Si las reemplazás, mantené los nombres o actualizá el `src`, el `alt`, las medidas `width` y `height` y el pie de figura con la autoría correcta.

- **Insignia de la licencia:** el pie de página carga la imagen oficial CC BY 4.0 desde `mirrors.creativecommons.org`. Para que funcione sin conexión, descargala a una carpeta `img/` y cambiá su `src`.

- **Contenido:** editá los textos directamente en `index.html`.
- **Compartir:** el botón de la portada usa el menú nativo del dispositivo y, si no existe, copia el enlace.
- **Colores:** están como variables CSS al inicio de `style.css` (`:root`). Si los cambiás, volvé a comprobar que el texto mantenga 7:1 de contraste.
- **Ilustraciones:** son SVG propios dentro del HTML. Si agregás capturas de pantalla, incluí siempre un texto alternativo y citá la fuente. Las capturas de Google Meet son material de Google.
- **Referencias:** al actualizar el recurso, revisá los enlaces y las fechas de recuperación.

## Uso de inteligencia artificial

Las cuatro imágenes de la carpeta `img/` (`portada.jpg`, `ventajas.jpg`, `pantalla.jpg` y `seguridad.jpg`) fueron **generadas con ChatGPT (OpenAI, 2026)** a partir de indicaciones de Bruno Menza. Esto se declara en el pie de cada figura y en el pie de página del sitio.

- Son ilustraciones, no capturas oficiales de Google Meet.
- El estatus de derechos de autor del contenido generado con IA puede variar según la jurisdicción. Las imágenes se ofrecen bajo CC BY 4.0 en la medida en que corresponda.
- El logotipo de Google Meet que aparece en `portada.jpg` es marca de Google LLC y no está cubierto por la licencia CC BY 4.0.
- Si reemplazás las imágenes por otras, actualizá los pies de figura y esta sección.

## Aviso

Google y Google Meet son marcas de Google LLC. Este recurso es independiente y no está afiliado a Google, ANEP, DGETP ni DGES. Las funciones descritas pueden variar según la edición de Google Workspace for Education y la configuración de cada institución.

## Referencias principales

- Administración Nacional de Educación Pública. (s. f.). *Sitio institucional de ANEP*. https://www.anep.edu.uy
- Agencia de Gobierno Electrónico y Sociedad de la Información y del Conocimiento. (s. f.). *Declaración de accesibilidad*. https://www.gub.uy/agencia-gobierno-electronico-sociedad-informacion-conocimiento/declaracion-accesibilidad
- Creative Commons. (s. f.). *Atribución 4.0 Internacional (CC BY 4.0)*. https://creativecommons.org/licenses/by/4.0/deed.es
- Google. (s. f.). *Ayuda de Google Meet*. https://support.google.com/meet
- Google Workspace Updates. (2023, 28 de septiembre). *The next phase of digital whiteboarding for Google Workspace* [Entrada de blog]. https://workspaceupdates.googleblog.com/2023/09/the-next-phase-of-digital-whiteboarding-for-google-workspace.html
- OpenAI. (2026). *ChatGPT* [Modelo de lenguaje de gran tamaño]. https://chatgpt.com
- Poder Ejecutivo. (2022, 22 de diciembre). *Decreto 406/022*. https://www.impo.com.uy/bases/decretos/406-2022
- UNESCO. (2019). *Recomendación sobre los recursos educativos abiertos (REA)*. https://www.unesco.org/es/legal-affairs/recommendation-open-educational-resources-oer
- World Wide Web Consortium. (2018). *Web content accessibility guidelines (WCAG) 2.1*. https://www.w3.org/TR/WCAG21/

La lista completa, en formato APA 7.ª edición, está en la sección **Referencias** de la página.
