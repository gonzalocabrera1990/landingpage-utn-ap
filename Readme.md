# 🌍 Viajes Landing Page


Una **Landing Page** desarrollada con **HTML, CSS y JavaScript** para mostrar una selección de destinos turísticos, junto con su descripción y precio.

Surge de la cursada Argentina Programa 4.0 | UTN.

La información se carga dinámicamente desde un archivo **JSON**, permitiendo modificar el contenido sin alterar la lógica de la aplicación.
Utiliza una API externa para mostrar pronostico del tiempo.

---

## ✨ Características

* 📍 Listado de destinos turísticos.
* 💲 Visualización de precios.
* 📄 Carga dinámica de datos mediante `fetch()`.
* 📱 Diseño responsive.
* ⚡ Proyecto ligero y sin dependencias externas.
* 🎯 Ideal como proyecto de práctica con JavaScript.
* 🚀 API weatherapi para mostrar pronostico extendido del tiempo.


---

## 🛠 Tecnologías

* HTML5
* CSS3
* JavaScript (ES6)
* JSON

---

## 📁 Estructura del proyecto

```text
viajes-landing-page/
│
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── script.js
├── db/
│   └── promotores.json
│   └── recomendados.json
│   └── viajes.json
└── README.md
```

---

## 🚀 Ejecución local

> **Importante**
>
> La aplicación utiliza `fetch()` para cargar el archivo JSON. Por este motivo **no debe abrirse directamente con doble clic** (`file://`), ya que el navegador bloqueará la solicitud por políticas de seguridad (CORS).

### Opción 1: Live Server (Recomendada)

1. Abrir el proyecto en **Visual Studio Code**.
2. Instalar la extensión **Live Server**.
3. Hacer clic derecho sobre `index.html`.
4. Seleccionar **Open with Live Server**.

La aplicación se abrirá en una dirección similar a:

```text
http://127.0.0.1:5500/
```

---

## 📄 Fuente de datos

Toda la información se obtiene desde:

```text
db/promotores.json
db/recomendados.json
db/viajes.json
```

Para agregar o modificar información solo es necesario editar estos archivo respetando el formato JSON.

---

## 📜 Licencia

Este proyecto fue desarrollado con fines educativos y de práctica. Puede utilizarse libremente como base para proyectos personales o de aprendizaje.

---

## 👨‍💻 Autor

Desarrollado como proyecto de práctica para aplicar conceptos de:

* HTML5
* CSS3
* JavaScript
* Manipulación del DOM
* Consumo de archivos JSON mediante `fetch()`
