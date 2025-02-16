---
layout: post
title: Cambios sugeridos al sitio actual
permalink: cambios-sugeridos
---

## En esta página:

- [Introducción](#introducción)
- [Plugins](#plugins)
  - [Desactivar](#desactivar)
  - [Borrar](#borrar)
  - [Agregar y activar](#agregar-y-activar)
- [Organización del contenido](#organización-del-contenido)
  - [Crear una página de entradas](#crear-una-página-de-entradas)
  - [Menú superior](#menú-superior)
- [Uso de la galería de WordPress](#uso-de-la-galería-de-wordpress)
- [Página inicial](#página-inicial)
- [Cambios al tema](#cambios-al-tema)

---

## Introducción

Este documento presenta recomendaciones para optimizar el sitio web actual y mejorar su accesibilidad y funcionalidad. Estos cambios están diseñados pensando en la facilidad de uso para personas que navegan con lectores de pantalla.

---

## Plugins

### Desactivar
Se pueden reactivar si son necesarios en algún momento.

- **All-in-One WP Migration**  
- **FileBird Lite**  
- **FileOrganizer**  
- **Hostinger Easy Onboarding**  
- **Hostinger Tools**  
- **One Click Accessibility**
- **LiteSpeed Cache**

### Borrar
Es probable que ya no sean necesarios.

- **Starter Templates**

### Agregar y activar

- **Classic Widgets:** Ya se activó para mantener una estructura de widgets más sencilla y compatible con lectores de pantalla.  
- **Disable Comments:** Para desactivar los comentarios globalmente en el sitio.  
- **WP Mail SMTP:** En caso de que se desee enviar formularios desde una cuenta de Gmail en lugar de la dirección actual (**u902433631@srv1064.main-hosting.eu**). Requiere configurar la cuenta de Gmail.

---

## Organización del contenido

### Crear una página de entradas

- Crear una página llamada **"Avisos"** donde se listarán todas las entradas en formato de blog.  
- Configurar esta página en los **Ajustes de lectura** como la página de entradas del sitio.

### Menú superior

- Añadir una nueva opción al menú superior llamada **"Avisos"**.  
- Incluir un submenú con categorías relacionadas con los avisos, como:  
  - Noticias  
  - Eventos  
  - Reconocimientos  
  - Conferencias  
  - Cursos  
- Estas categorías deben crearse previamente desde la sección **Entradas > Categorías**.

---

## Uso de la galería de WordPress

- Reemplazar el plugin **FileBird Lite** con la galería nativa de WordPress para gestionar imágenes.  
- La galería nativa es más accesible y fácil de usar con el teclado, lo que la hace ideal para este caso.
- Cambiar la vista de la galería de medios a "Vista de cuadrícula" más amigable con el teclado.

---

## Página inicial

- Analizar si el formulario de contacto es necesario en la página principal.  
  - En caso de que no sea imprescindible, reemplazarlo por una sección con por ejemplo:  
    - La dirección de la fundación. 
    - Una descripción detallada de la organización y los servicios que ofrece.
    - Datos para colaboración como donativos, número de cuenta bancaria, servicio social, etc. 
  - Mover el formulario de contacto a una página separada llamada **"Contáctanos"**.
- Se recomienda modificar la imagen de fondo del sitio cada 2 o 3 meses para dar una sensación de actualización y dinamismo, así como publicar entradas con regularidad.

## Cambios al tema

- En el archivo **includes/core.php** en las líneas 228 y 230 se dibuja el título de la página sin encabezado: <code>\<div class="entry-title">\</div></code>. Sustituir por un encabezado: <code>h2</code> con su respectivo <code>aria-description="Título de la página"</code>.
- En el archivo **includes/core.php** en la línea 305 dibujan el título del sitio sin encabezado: <code>$heading_tag = ( is_front_page() || ( is_home() ) ) ? 'h1' : 'div';</code>. Sustituir que siempre sea un encabezado: <code>$heading_tag = 'h1';</code> con su respectivo <code>aria-description="Título del sitio"</code>.

---

Estas sugerencias están diseñadas para hacer el sitio más accesible y funcional, mejorando la experiencia tanto para los administradores como para los visitantes.