# 🛡️ Proyecto 1: Portfolio Profesional | HTML5 & CSS3

Desarrollo y maquetación de una interfaz web profesional construida exclusivamente con **HTML5 semántico** y **CSS3 puro**, enfocada en la exposición de activos técnicos, proyectos de infraestructura y trayectoria en ciberseguridad.

---

## 🎯 Cyber-Link & Justificación Técnica

> **"Comprender la anatomía del cliente es el primer paso para defenderlo."**

En el ámbito de la seguridad ofensiva y defensiva, dominar la estructura básica del front-end es fundamental:

* **Inspección del DOM y Superficie de Ataque:** Conocer la jerarquía estricta de elementos HTML permite identificar vulnerabilidades del lado del cliente como *Cross-Site Scripting (XSS)*, inyecciones de código y manipulaciones de la interfaz (*UI Redressing* / *Defacements*).
* **Validación e Higienización en Formularios:** Entender el funcionamiento nativo de atributos de formulario (`required`, tipos de entrada, métodos de envío) sienta las bases para diseñar flujos que requieran validación robusta y defensas contra *Cross-Site Request Forgery (CSRF)*.
* **Optimización y Carga de Activos:** La maquetación ligera sin dependencias externas pesadas reduce vectores de ataque asociados a librerías de terceros desactualizadas.

---

## 🛠️ Arquitectura y Tecnologías Aplicadas

* **HTML5 Semántico:** Estructuración limpia mediante etiquetas nativas (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) garantizando accesibilidad y validación W3C.
* **CSS3 Moderno:**
  * **Variables CSS (`:root`):** Centralización de tokens de diseño para paletas de color y tipografía.
  * **CSS Grid & Flexbox:** Maquetación declarativa para galerías de proyectos y barras de navegación adaptativas.
  * **Diseño Responsive:** Adaptabilidad móvil/tablet/desktop mediante *Media Queries* fluidas.
* **Control de Versiones:** Repositorio público independiente con gestión de cambios en Git.

---

## 📁 Estructura del Repositorio

```text
├── index.html       # Estructura semántica, metadatos y marcado de contenido
├── styles.css       # Reset, variables, maquetación Grid/Flexbox y media queries
└── README.md        # Documentación técnica del módulo
