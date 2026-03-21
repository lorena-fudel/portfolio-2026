# LF Portfolio 2026 ✨

Un portafolio personal moderno, interactivo y completamente responsivo diseñado para mostrar mis proyectos, experiencia y habilidades como desarrolladora web. Esta versión es completamente estática y no requiere de un servidor backend complejo, por lo que es ideal para ser alojada en GitHub Pages, GitLab Pages o Netlify.

## 🚀 Características Principales

- **Diseño Moderno:** Estética limpia utilizando *Glassmorphism* (efectos de cristal) e interfaces suavizadas.
- **Modo Claro / Oscuro:** Cambio de tema integrado con persistencia automática en `localStorage`, utilizando iconos SVG dinámicos y transiciones de color globales.
- **Carrusel de Proyectos Interactivo:** Desplazamiento de tarjetas (Smooth Scroll y Scroll Snapping) con navegación manual mediante botones y modo de reproducción automática (Autoplay) cada 3 segundos (configurable), que se pausa inteligentemente cuando el usuario apoya el cursor o usa táctil en el móvil.
- **Formulario Funcional:** Integrado nativamente con [Formspree](https://formspree.io/) para enviar directamente los correos a tu bandeja de entrada real. Sin necesidad de configurar SMTP en Javascript.
- **Responsivo (Mobile-First):** Se adapta nativamente a pequeñas pantallas interactuando perfectamente con dispositivos móviles y monitores anchos usando CSS Grid y Flexbox.

## 🛠️ Tecnologías Utilizadas

- **Documento:** HTML5 Semántico.
- **Estilos:** CSS3 Vanilla Avanzado (Variables globales en `:root`, atributos `data-theme`, animaciones fluidas `cubic-bezier`, Grid/Flexbox). Cero frameworks sobrecargados.
- **Interactividad:** JavaScript (Vanilla ES6) para todo el dinamismo (Carrusel lógico y Theme Switcher).
- **Tipografía y Vectoriales:** Google Fonts (Inter, Outfit) e Iconos FontAwesome + SVGs insertados (Inline).

## 📂 Estructura del Proyecto

```text
web-estatica/
├── index.html       # Archivo principal de estructuración (One-Page)
├── src/
│   ├── style.css    # Hoja de estilos unificada (Variables, Temas, Media Queries)
│   └── images/      # Carpeta de todos los componentes visuales (Perfil, Favicon, Capturas)
├── README.md        # Documentación del proyecto
```

## 💻 Cómo ejecutarlo

Al ser un proyecto puramente estático, no necesitas realizar de instalaciones complejas como `npm install`.

1. **Clona este repositorio:**
   ```bash
   git clone https://github.com/lorena-fudel/portfolio-2026.git
   ```
2. **Entra al directorio:**
   ```bash
   cd portfolio-2026/
   ```
3. **Pruébalo:**
   Simplemente haz doble clic en el archivo `index.html` para que se abra tu navegador predeterminado (o utiliza una extensión como *Live Server* en VSCode para agilizar el desarrollo de futuras versiones).

## 📧 Acerca de mí

**Lorena** - Fullstack Developer
Apasionada de la tecnología, enfocada en la estrategia, el diseño y el código desde Canarias hacia el mundo.

- **Email:** [fmrlorena@gmail.com](mailto:fmrlorena@gmail.com)
- **Repositorio Principal:** [Lorena F. GitHub](https://github.com/lorena-fudel)
