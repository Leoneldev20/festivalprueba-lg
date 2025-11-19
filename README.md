# Techno & EDM Festival – Landing Page de Festival Electrónico

Landing page interactiva para un festival de música electrónica, enfocada en performance, estética moderna y una experiencia de usuario fluida.
La interfaz integra elementos multimedia y componentes interactivos desarrollados en JavaScript, como una galería dinámica y animaciones suaves que mejoran la navegación.
Además, se implementaron automatizaciones con Gulp para optimizar el rendimiento en el entorno de producción.

---

## Demo 

https://festivalprueba-frontend-lg.netlify.app

---

## Tecnologías utilizadas

- **HTML5** — Estructura semántica de la página.
   
- **SCSS** — Uso de SASS para estilos escalables (variables, mixins, partials y buenas prácticas de arquitectura CSS).

- **JavaScript ES6+** — Para la lógica de interacción (Galería interactiva, Scroll suave, Menú responsive y Comportamientos dinamicos).

- **Gulp** — Automatización de tareas (compilación de SCSS, minificación, live reload, etc).

---

## Estructura del proyecto

festivalprueba-lg/

├── src/ # Código fuente

│ └── img/ # Imágenes usadas en la landing

│ └── js/ # Código JavaScript

│ └── scss/ # Archivos SCSS para los estilos

├── video/ # Recursos de video 

├── .gitignore # Archivos o carpetas ignoradas por Git

├── gulpfile.js # Definición de tareas Gulp 

├── index.html # Página principal del festival

└── package.json # Dependencias y scripts del proyecto 

## Buenas prácticas aplicadas

- **Código modular**: SCSS dividido en parciales para mantener los estilos organizados y escalables.
    
- **Mobile-first**: La estructura de estilos y layout parte desde dispositivos móviles hacia pantallas más grandes.
    
- **Optimización de assets**: Minificación de CSS y JS, optimización de imágenes y videos mediante tareas de Gulp.
    
- **Semántica HTML**: Uso adecuado de etiquetas semánticas para mejor accesibilidad.
   
- **Convenciones BEM** para organizar clases y evitar colisiones.
   
- **JavaScript limpio y enfocado**: Funciones específicas para galeria, animaciones, interacción y manipulación del DOM.
   
- **Sistema de build automatizado** con Gulp para mantener un flujo de trabajo eficiente y reproducible.
   
- **Versionado con Git** siguiendo commits descriptivos y organización clara del historial.

