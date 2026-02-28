# 🏚️ Una nueva casa

Proyecto de historia interactiva desarrollado únicamente con **HTML**, como parte del laboratorio de desarrollo web.

## 📖 Descripción

"Una nueva casa" es una historia interactiva de misterio tipo crimen en la que el jugador explora una casa recientemente adquirida.

A medida que avanza por diferentes habitaciones, descubre pistas relacionadas con un antiguo incidente ocurrido en la propiedad. Dependiendo de las decisiones tomadas, la historia puede terminar en distintos finales.

El proyecto fue diseñado para practicar:

- Estructura de múltiples páginas HTML
- Uso correcto de rutas relativas y absolutas
- Organización de carpetas
- Uso de etiquetas semánticas
- Navegación no lineal

---

## 🗂️ Estructura del proyecto

- `index.html` es el punto de inicio de la historia.
- Las escenas están distribuidas en diferentes archivos dentro de la carpeta `/house`.
- Las imágenes están almacenadas en la carpeta `/imagenes`.
- El sótano representa un final negativo.
- El ático representa el final positivo.

---

## 🧭 Navegación

La historia **no es lineal**.  
El usuario puede:

- Explorar diferentes habitaciones en el orden que desee.
- Volver a escenas anteriores (loops usando `../`).
- Encontrar pistas que influyen en sus decisiones.
- Llegar a distintos finales.

Cada página incluye:

- Breadcrumbs para mostrar la ubicación actual.
- Opciones de navegación para continuar la historia.
- Un enlace para volver al inicio en los finales.

---

## 🛠️ Tecnologías utilizadas

- HTML5
- No se utilizó CSS
- No se utilizó JavaScript

---

## 🧩 Etiquetas HTML utilizadas

El proyecto hace uso de etiquetas semánticas como:

- `<header>`
- `<main>`
- `<footer>`
- `<nav>`
- `<article>`
- `<section>`
- `<figure>`
- `<img>`
- `<details>`
- `<summary>`

No se utilizó la etiqueta `<div>`.

---

## 🔗 Acceso

El proyecto puede visualizarse en el servidor de la clase mediante la URL : [Link lab3](http://35.239.29.236/24852/Lab3_web/)

---

## 👤 Autor

Juan Gualim  
Laboratorio 2 - Sistemas y tecnologías web
