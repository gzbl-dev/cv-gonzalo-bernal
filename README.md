# 🧑‍💻 CV Gonzalo Bernal López

Web personal para mostrar mi experiencia profesional, proyectos y skills.

---

## 🚀 Tech Stack

- **HTML5** → estructura
- **CSS3** → estilos base
- **TailwindCSS** (CDN) → utilidades de diseño responsive
- **Material Symbols** → iconografía
- **devicon** (CDN) → logos de tecnologías

---

## ✨ Características

- **Selector de idioma ES/EN funcional**, persistido en `localStorage`.
- **Modo oscuro funcional** (botón en el header), respeta la preferencia del sistema y se guarda en `localStorage`.
- **Botón "Descargar CV"** que enlaza al PDF (ver `src/docs/`).
- **Avatar con fallback automático**: si no hay foto en `src/images/foto-gonzalo.jpg`, se genera un avatar con las iniciales.
- **Sección de Educación** añadida como bloque propio.
- **Botón "volver arriba"** flotante.
- Iconos de tecnologías vía CDN (sin necesidad de mantener imágenes locales).
- **Animaciones AOS** (Animate On Scroll) y efectos hover en tarjetas, iconos y enlaces.
- **Menú hamburguesa** para móvil.
- **Scrollspy**: el enlace de navegación activo se resalta según la sección visible.
- **SEO**: meta description, Open Graph y favicon propio (SVG inline).
- **Indicadores de nivel** (puntos) en cada skill técnica.
- **Enlaces "Ver en GitHub"** en cada proyecto, apuntando a su repositorio concreto.
- **Formulario de contacto funcional** vía `mailto:` (abre el cliente de correo con asunto y mensaje precargados).
- Mejoras de accesibilidad: `aria-label`, `aria-hidden`, estilos `:focus-visible`.

---

## 🌐 Ver en vivo

👉 [https://gzbl-dev.github.io/cv-gonzalo-bernal/](https://gzbl-dev.github.io/cv-gonzalo-bernal/)

---

## 💻 Cómo verlo en local

Abre `index.html` directamente en el navegador, o sirve la carpeta con
cualquier servidor estático (por ejemplo `npx serve .`).

---
