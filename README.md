Portafolio web personal desarrollado con HTML5 semántico y CSS3 responsivo. Evaluación P2 - Desarrollo de Frontend

Portafolio Web Personal — Simón Millanguir

Este proyecto corresponde a la Evaluación 2 (P2) de la asignatura **Desarrollo de Frontend (ICINF1107)** de la carrera Ingeniería Civil en Informática, Universidad Católica de Temuco.

Descripción del Proyecto
Se trata de una interfaz web personal de portafolio desarrollada con etiquetas semánticas de HTML5 y estilos en CSS3. El sitio fue diseñado con un enfoque *responsive* (adaptable a múltiples dispositivos) y cumpliendo con pautas básicas de accesibilidad web (WCAG).

Secciones:
- **Sobre mí:** Presentación personal y perfil.
- **Trabajos del semestre:** Muestra los proyectos y lecturas realizadas (*La Fábula del Diseñador Centrado en el Usuario*, *Simon's Store* y *Portafolio Web*).
- **Contacto:** Formulario funcional maquetado con etiquetas accesibles.

Tecnologías Utilizadas
- **HTML5**: Estructura semántica (`header`, `nav`, `main`, `section`, `article`, `footer`)
- **CSS3**: Layouts con Flexbox y CSS Grid, variables CSS y Media Queries para el diseño responsivo.
- **Git & GitHub**: Control de versiones y alojamiento del proyecto.

Decisiones de Diseño
1. **Audiencia y Propósito**: Orientado a reclutadores técnicos y docentes. La prioridad visual es destacar el perfil técnico y los proyectos realizados durante el semestre.
2. **Jerarquía Visual y Accesibilidad**:
   - Alto contraste entre fondo y texto para facilitar la lectura.
   - Navegación visible mediante estados `:focus` y `:hover` pensada en usuarios que navegan con teclado.
   - Formularios estructurados con etiquetas `<label>` enlazadas explícitamente a sus campos (`<input>`).
   - Imágenes con atributos `alt` descriptivos para lectores de pantalla.
3. **Puntos de Quiebre (Breakpoints)**:
   - **Móvil (< 600px)**: Diseño vertical en una sola columna y menú simplificado.
   - **Tablet (600px - 899px)**: Distribución en 2 columnas para la sección de proyectos.
   - **Escritorio (≥ 900px)**: Navegación horizontal en el header y distribución en 3 columnas para proyectos.


Cómo Descargar desde GitHub

1. **Abrir el Repositorio desde Github, y descargarlo en archivo zip.**
2. **Abrir el archivo en Visual Estudio.**


________________________________________________________
                    USO DE IA
________________________________________________________

En este proyecto se utilizó Inteligencia Artificial (IA) como asistente de desarrollo para los siguientes apartados:

1. **Integración del Formulario de Contacto (Gmail):**
   - Asistencia en la lógica de JavaScript para capturar los datos del formulario y redireccionar dinámicamente a la interfaz de composición de Gmail, garantizando que el mensaje sea dirigido correctamente al correo del autor (`smillanguir2026@alu.uct.cl`).

2. **Diseño y Estilos CSS (`css/style.css`):**
   - Apoyo en la maquetación y reglas CSS para el diseño responsivo (*media queries*), estructuración mediante Flexbox (alineación de imagen y texto en la sección "Sobre mí") y mejora de la jerarquía visual de las tarjetas de proyectos.

3. **Documentación (`README.md`):**
   - Soporte en la organización, estructuración y redacción del texto explicativo del proyecto para la evaluación.
