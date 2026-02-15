Proyecto: Blog Biblioteca
Documento: Preparación del Entorno
Autor: Jonathan Pauth
Versión: 1.0

Este manual describe los pasos necesarios para preparar y ejecutar el blog en un entorno local.

1. Ingredientes (Requisitos)

Un navegador web moderno (Google Chrome, Firefox, Brave o Edge).

Un editor de código (recomendado: VS Code) para realizar modificaciones.

Conexión a internet (solo para cargar fuentes externas si se agregan).

2. Preparación (Instalación)

Siga estos pasos exactos para preparar el sistema:

Obtener el código:

Clonar el repositorio: git clone [URL_DEL_REPOSITORIO]

O descargar y extraer el archivo .zip.

Verificar estructura:
Asegúrese de que los archivos mantengan esta jerarquía:

index.html
├── CSS/style.css
├── JS/menulateral.js


3. Cocción (Ejecución)

Para ver el blog funcionando:

Localice el archivo index.html.

Haga clic derecho sobre él y seleccione "Abrir con..." -> Su navegador preferido.

O simplemente arrastre el archivo hacia una pestaña abierta del navegador.

4. Modificaciones Rápidas

¿Cómo agregar un post? Copie un bloque <article> dentro de la etiqueta <section class="contenido"> en index.html.

¿Cómo cambiar colores? Modifique las variables en :root dentro de CSS/style.css.

¿Cómo actualizar la barra lateral? Edite los enlaces en el div#mySidebar del HTML.

Nota: Al ser una página estática, no se requiere la instalación de Node.js, PHP o bases de datos externas.