---
layout: post
title: Uso de formularios de contacto con WP Forms
permalink: formularios-wpforms
---

### En esta página:

- [Introducción](#introducción)
- [Acceder al formulario existente](#acceder-al-formulario-existente)
- [Editar el formulario "Contacto"](#editar-el-formulario-contacto)
- [Identificar en qué página está activo el formulario](#identificar-en-qué-página-está-activo-el-formulario)
- [Crear un nuevo formulario y añadirlo a una página](#crear-un-nuevo-formulario-y-añadirlo-a-una-página)
- [Consejos para formularios accesibles](#consejos-para-formularios-accesibles)

---

En esta guía aprenderás cómo navegar, editar y gestionar un formulario ya existente llamado **"Contacto"**, y cómo identificar en qué página está activo. Además, encontrarás instrucciones para crear un nuevo formulario y añadirlo a una página.

---

## Acceder al formulario existente

1. **Navega a WP Forms:**  
   - Desde la barra lateral izquierda, utiliza **Tab** o las flechas para navegar hasta **WP Forms**.  
   - Pulsa **Enter** para abrir la sección de formularios.

2. **Selecciona el formulario "Contacto":**  
   - Usa **Tab** para desplazarte por la lista de formularios creados.  
   - Escucha el nombre "Contacto" anunciado por el lector de pantalla.  
   - Pulsa **Enter** en el enlace **Editar** junto al formulario para abrirlo.

---

## Editar el formulario "Contacto"

1. **Navegar por los campos:**  
   - Usa **Tab** para moverte entre los campos del formulario, como "Nombre", "Correo electrónico" y "Mensaje".  
   - Pulsa **Enter** en cualquier campo para editarlo.  
   - Realiza cambios como:  
     - Modificar el texto de la etiqueta.  
     - Hacer un campo obligatorio o no.  
     - Ajustar el tamaño del campo.

2. **Añadir nuevos campos:**  
   - Usa **Tab** para llegar a la barra lateral derecha donde están los campos disponibles.  
   - Selecciona un campo, como "Número de teléfono", y pulsa **Enter** para añadirlo al formulario.  

3. **Guardar los cambios:**  
   - Usa **Tab** para llegar al botón **Guardar** y pulsa **Enter** para guardar las modificaciones realizadas.

---

## Identificar en qué página está activo el formulario

1. Desde la lista de formularios en **WP Forms**, navega hasta el formulario **"Contacto"**.  
2. Usa **Tab** para encontrar la columna llamada **Locations**.  
3. El lector de pantalla anunciará en qué página está insertado el formulario, por ejemplo:  
   - "Página: Contacto".  
4. Si necesitas verificar el formulario en la página pública:  
   - Navega a **Páginas** desde la barra lateral.  
   - Encuentra la página mencionada y pulsa **Ver** para comprobar cómo luce el formulario.

---

## Crear un nuevo formulario y añadirlo a una página

1. **Crear un nuevo formulario:**  
   - En **WP Forms**, selecciona la opción **Añadir nuevo** y pulsa **Enter**.  
   - Usa **Tab** para elegir la plantilla **Formulario de contacto simple** y pulsa **Enter**.  
   - Personaliza los campos según tus necesidades y guarda los cambios.
   - Regresa a la lista de formularios en **WP Forms**, navega hasta nuevo formulario creado y busca cual es su número de identificador o ID.

2. **Insertar el formulario en una nueva página:**  
   - Ve a **Páginas > Añadir nueva** desde la barra lateral.  
   - Escribe un título para la página, como "Formulario de registro".  
   - Usa **Tab** para acceder al área de contenido e inserta el shortcode del formulario:  
     `[wpforms id="X"]`, reemplazando **X** con el ID del nuevo formulario.  
   - Guarda y publica la página.

---

## Consejos para formularios accesibles

- **Usa etiquetas claras:** Cada campo debe tener un nombre descriptivo.  
- **Simplifica los formularios:** Limita la cantidad de campos para mejorar la experiencia del usuario.  
- **Verifica la funcionalidad:** Revisa que todos los campos y el botón de envío funcionen correctamente.

En resumen, WP Forms facilita la gestión de formularios de contacto en WordPress. Con estas instrucciones, podrás editar, localizar y crear formularios de manera accesible y eficiente.

![Captura de pantalla del área de administración de WordPress donde se muestra el apartado WpForms, especificamente la sección de edición del formulario de contacto del sitio.](images/formularios-wpforms.png)