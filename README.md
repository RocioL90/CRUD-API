# CRUD de Usuarios - TP Diseño Web

Este proyecto es una aplicación web simple para gestionar usuarios (Crear, Leer, Actualizar y Eliminar) utilizando la API pública [CRUD CRUD](https://crudcrud.com/).

## Características

- Listado de usuarios en una tabla.
- Agregar nuevos usuarios.
- Editar usuarios existentes mediante un popup modal.
- Eliminar usuarios.
- Validación de campos obligatorios.
- Notificaciones visuales usando SweetAlert.
- Interfaz moderna y responsive.

## Tecnologías utilizadas

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**
- **jQuery** y **jQuery UI** (para el popup modal)
- **SweetAlert** (para notificaciones)
- **API pública:** [CRUD CRUD](https://crudcrud.com/)

## Estructura de archivos

```
├── index.html
├── style.css
├── scripts.js
```

## Cómo usar

1. **Obtén tu endpoint de CRUD CRUD:**  
   Ve a [https://crudcrud.com/](https://crudcrud.com/) y copia tu URL única.
2. **Configura la URL en `scripts.js`:**  
   Cambia la constante `url` al inicio del archivo por tu endpoint, por ejemplo:  
   ```javascript
   const url = 'https://crudcrud.com/api/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx/usuarios'
   ```
3. **Abre `index.html` en tu navegador.**
4. Utiliza la tabla para agregar, editar o eliminar usuarios.

## Funcionalidad principal

- **Agregar usuario:** Completa todos los campos y haz clic en "AGREGAR".
- **Editar usuario:** Haz clic en "VER" en la fila deseada, edita los datos y presiona "UPDATE".
- **Eliminar usuario:** Haz clic en "BORRAR" en la fila deseada.

## Notas

- Todos los campos son obligatorios.
- El popup de edición se cierra automáticamente al actualizar.
- El código utiliza promesas y XMLHttpRequest para interactuar con la API.
- CRUD CRUD almacena los datos por 24 horas.

## Créditos

- [SweetAlert](https://sweetalert.js.org/)
- [jQuery](https://jquery.com/)
- [jQuery UI](https://jqueryui.com/)
- [CRUD CRUD](https://crudcrud.com/)

---
# CRUD-API
