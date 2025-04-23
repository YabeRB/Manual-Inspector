---
id: manual-inspector
title: Inspector Manual
sidebar_label: Inspector Manual
sidebar_position: 1
toc: false
---

# Manual del Inspector de Elementos

El inspector de elementos de tu navegador es una herramienta poderosa para analizar y modificar páginas web en tiempo real.

---

## ¿Cómo acceder?

Para abrir el Inspector:

- 🖱️ Haz clic derecho sobre cualquier parte de la página.
- ⌨️ Pulsa `Ctrl + Shift + I` (o `Cmd + Option + I` en macOS).

---

## 📂 Principales secciones

### 1. **Elements**  
Aquí puedes **ver y editar el HTML** de la página. También puedes:

- Ver los estilos CSS aplicados al momento.
- Activar/desactivar reglas CSS temporalmente.
- Cambiar texto o etiquetas directamente.
- Ver estructura DOM en forma de árbol.

📌 **Ejemplo de uso:** Cambiar el color de un botón antes de modificar el CSS real.

---

### 2. **Console**  
Permite **ver errores de JavaScript** y ejecutar comandos.

- Accede al entorno JS de la página.
- Usa comandos como `document.querySelector()` para manipular elementos.
- Visualiza mensajes con `console.log()`.

📌 **Ejemplo de uso:** Depurar funciones de formularios o scripts de interacción.

---

### 3. **Network**  
Herramienta para **ver las peticiones de red**:

- Carga de imágenes, scripts, y otros recursos.
- Ver tiempos de respuesta.
- Revisar llamadas AJAX o fetch.
- Analizar encabezados y respuestas HTTP.

📌 **Ejemplo de uso:** Comprobar si una API devuelve los datos esperados.

---

## Tips

- ✏️ Puedes **modificar texto directamente en el HTML** y ver los cambios al instante (útil para maquetado rápido).
- 🕵️ Usa el **icono de selección** (arriba a la izquierda del inspector) para inspeccionar elementos específicos pasando el mouse por ellos.
- 🔁 Los cambios hechos en el inspector **no se guardan permanentemente**, sirven para pruebas en vivo.

---