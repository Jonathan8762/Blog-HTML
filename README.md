# Blog: Más Allá del Velo y la Espada

Este proyecto consiste en un blog técnico-teológico desarrollado bajo el marco de trabajo Scrum, priorizando la agilidad y la entrega de software funcional. La documentación aquí presentada es "just-in-time" y se centra en lo estrictamente necesario para el despliegue y mantenimiento.

🏗️ Arquitectura del Sistema

El sistema sigue un modelo de separación de responsabilidades para garantizar la escalabilidad:

Estructura (HTML5): Uso de etiquetas semánticas (<main>, <article>, <nav>, <footer>) para optimizar el SEO y la accesibilidad.

Estilos: Diseño basado en Variables CSS (Custom Properties) para una gestión centralizada de colores y tipografías. Implementa un diseño responsivo mediante Flexbox y Media Queries.

Lógica: Sistema modular para la navegación. La lógica del menú lateral se encuentra aislada en JS/barralateral.js.

📂 Estructura de Archivos

/
├── Blog1.html          # Blog Principal
├── index.html          # Punto de entrada principal
├── /CSS
│   └── style.css       # Hoja de estilos global
├── /JS
│   └── barralateral.js      # Lógica del menú lateral interactivo
├── /docs               # Documentación técnica adicional
│   └── COOKBOOK.md     # Guía rápida de preparación
└── /IMG                # Recursos multimedia


🚀 Manual de Preparación (Quick Start)

Para poner en funcionamiento el blog localmente, siga estos pasos:

Clonación: Descargue o clone el repositorio desde GitHub.

Dependencias: No requiere servidores ni preprocesadores. Es una aplicación estática pura.

Ejecución: Abra index.html en cualquier navegador moderno (Chrome, Firefox, Edge).

Navegación: Utilice el botón "☰ Menú" para navegar por el índice de secciones mediante anclas (#ID).

🛠️ Pruebas (Tests)

Validación Semántica: El código cumple con los estándares de W3C.

Navegación: Se ha verificado que todos los enlaces de anclaje (#inicio, #raices, #teologia) dirijan al usuario a la sección correcta con scroll-behavior: smooth.

Interactividad: El menú lateral ha sido probado en resoluciones móviles y de escritorio.

📈 Metodología Scrum

Este proyecto se gestionó mediante un tablero en Jira, dividiendo el desarrollo en historias de usuario centradas en la experiencia del lector y la optimización del código.
https://martinezpauthjonathanenmanuel.atlassian.net/jira/software/projects/SCRUM/boards/1

Desarrollado por: Jonathan
Materia: Ingenieria Siftware
