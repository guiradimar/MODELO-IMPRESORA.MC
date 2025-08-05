# 🖨️ Buscador de Impresoras y Consumibles

Este proyecto es una aplicación web que permite **buscar modelos de impresoras por referencia** y obtener al instante:

- Los **consumibles compatibles** (cartuchos o tóner)
- La **capacidad** de cada consumible
- Un acceso directo a **Google**, en caso de no encontrar el modelo buscado en la base de datos

---

## 🛠️ ¿Cómo funciona?

1. Introduce un modelo de impresora o consumible en la barra de búsqueda (ej: `TS3350`, `HP 305`, etc.)
2. Verás dos ventanas:
   - **Consumibles compatibles**
   - **Impresoras compatibles**
3. Si no se encuentra, aparece un aviso en rojo y se ofrece un botón para buscar en Google automáticamente.

---

## 🎨 Características visuales

- Diseño limpio y responsivo
- Paneles diferenciados por color para claridad:
  - Azul → Consumibles
  - Naranja → Impresoras
- Mensaje de error destacado en rojo
- Botón de búsqueda en Google estilizado y visible

---

## 📁 Estructura del proyecto

```
📦 Buscador-impresoras
├── index.html                → Interfaz y lógica del buscador
├── consumibles_impresoras.js → Archivo con todos los datos estructurados en JSON
└── README.md                → Este archivo
```

---

## 🚀 Deploy

Este proyecto está desplegado automáticamente en [Netlify](https://www.netlify.com/) desde GitHub.

---

## 🔗 Enlace directo a la aplicación:

👉 [Accede al Buscador aquí](https://TUDOMINIO.netlify.app/)

---

## 👩‍💻 Creado por

**Arantxa (guiradimar)**  
Desarrollado con HTML, JavaScript y amor por la eficiencia 👊
