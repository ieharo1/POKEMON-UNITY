# 🅱️ BOOTSTRAP 5 DESDE CERO - GUÍA COMPLETA

**Bootstrap 5 desde Cero** es un sitio educativo completo diseñado para enseñar Bootstrap 5 desde los fundamentos hasta conceptos avanzados, con explicaciones claras, ejemplos prácticos y código listo para usar.

> *"Bootstrap es el framework CSS más popular del mundo. Con Bootstrap, puedes crear interfaces profesionales en minutos."*

---

## 🎯 ¿Qué es este Proyecto?

Este proyecto proporciona un recurso educativo gratuito para aprender Bootstrap 5, incluyendo:

- **Documentación completa** de cada tema
- **Ejemplos de código** listos para ejecutar
- **Ejercicios prácticos** para reforzar el aprendizaje
- **Sitio web educativo** con navegación intuitiva

---

## 📚 Contenido del Curso

### Módulo 1: Fundamentos

1. **Introducción**
   - Historia de Bootstrap
   - Bootstrap 5 vs versiones anteriores
   - Ventajas y casos de uso

2. **Instalación**
   - CDN (rápido y fácil)
   - npm/yarn (proyectos modernos)
   - Descarga directa
   - Configuración del proyecto

3. **Conceptos básicos**
   - Sistema Grid
   - Containers
   - Breakpoints
   - Clases utilitarias

### Módulo 2: Intermedio

4. **Ejemplos prácticos**
   - Navbar responsive
   - Cards y componentes
   - Formularios
   - Modals y alerts

5. **Buenas prácticas**
   - Personalización con Sass
   - Optimización de bundle
   - Accesibilidad
   - Browser support

### Módulo 3: Avanzado

6. **Casos reales**
   - Dashboards administrativos
   - Landing pages
   - E-commerce layouts
   - Blog templates

7. **Proyecto final**
   - Sitio web completo
   - Responsive y accesible
   - Deploy a producción

---

## 🗂️ Estructura del Proyecto

```
POKEMON-UNITY/
├── index.html          # Página principal
├── css/
│   └── styles.css      # Estilos del sitio
├── js/
│   └── main.js         # JavaScript del sitio
└── README.md
```

---

## 🚀 Cómo Usar este Proyecto

### Opción 1: Navegar el Sitio Web

1. Abre `index.html` en tu navegador
2. Navega por las secciones del curso
3. Haz clic en los temas para ver la documentación detallada

### Opción 2: Ejecutar los Ejemplos

1. Crea un archivo HTML
2. Agrega el CDN de Bootstrap
3. Copia los ejemplos de código

### Requisitos

- Navegador web moderno
- Editor de código
- Conocimientos básicos de HTML/CSS

---

## 📝 Ejemplos Rápidos

### Instalación con CDN

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Proyecto</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Tu contenido -->
    
    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

### Navbar Responsive

```html
<nav class="navbar navbar-expand-lg navbar-dark bg-primary">
  <div class="container">
    <a class="navbar-brand" href="#">Brand</a>
    <button class="navbar-toggler" type="button" 
            data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" href="#">Inicio</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Servicios</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contacto</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
```

### Grid System

```html
<div class="container">
  <div class="row">
    <div class="col-12 col-md-6 col-lg-4">
      <div class="card">Columna 1</div>
    </div>
    <div class="col-12 col-md-6 col-lg-4">
      <div class="card">Columna 2</div>
    </div>
    <div class="col-12 col-md-6 col-lg-4">
      <div class="card">Columna 3</div>
    </div>
  </div>
</div>
```

### Card Component

```html
<div class="card" style="width: 18rem;">
  <img src="imagen.jpg" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Título de la Card</h5>
    <p class="card-text">Descripción del contenido.</p>
    <a href="#" class="btn btn-primary">Action</a>
  </div>
</div>
```

### Modal Dialog

```html
<!-- Button trigger modal -->
<button type="button" class="btn btn-primary" 
        data-bs-toggle="modal" data-bs-target="#exampleModal">
  Abrir Modal
</button>

<!-- Modal -->
<div class="modal fade" id="exampleModal" tabindex="-1">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title">Título</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
      </div>
      <div class="modal-body">
        Contenido del modal...
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Cerrar</button>
        <button type="button" class="btn btn-primary">Guardar</button>
      </div>
    </div>
  </div>
</div>
```

### Utilidades Comunes

```html
<!-- Spacing -->
<div class="m-3">Margin en todos los lados</div>
<div class="p-3">Padding en todos los lados</div>
<div class="mt-4">Margin top</div>
<div class="mb-4">Margin bottom</div>

<!-- Colors -->
<div class="text-primary">Texto primario</div>
<div class="bg-success text-white">Fondo success</div>
<div class="text-danger">Texto danger</div>

<!-- Display -->
<div class="d-flex justify-content-center">Flex centrado</div>
<div class="d-none d-md-block">Oculto en móvil</div>
```

---

## 🎓 Metodología de Aprendizaje

### 1. Leer la Teoría
Cada tema comienza con una explicación clara del concepto.

### 2. Ver Ejemplos
Los ejemplos de código muestran la aplicación práctica.

### 3. Practicar
Los ejercicios te permiten aplicar lo aprendido.

### 4. Experimentar
Modifica los ejemplos para entender cómo funcionan.

---

## 🔧 Instalación

### CDN (Recomendado para empezar)

```html
<!-- CSS en <head> -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- JS antes de </body> -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
```

### npm

```bash
npm install bootstrap@5.3.0
```

```javascript
// En tu archivo JS principal
import 'bootstrap/dist/css/bootstrap.min.css';
import 'bootstrap/dist/js/bootstrap.bundle.min.js';
```

---

## 📖 Recursos Adicionales

### Documentación Oficial

- [Bootstrap 5 Docs](https://getbootstrap.com/docs/5.3/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)
- [Bootstrap Themes](https://themes.getbootstrap.com/)

### Herramientas Recomendadas

- **Bootstrap Builder** - Constructor visual
- **Bootswatch** - Temas gratuitos
- **Start Bootstrap** - Plantillas gratis

### Comunidades

- [GitHub - Bootstrap](https://github.com/twbs/bootstrap)
- [Stack Overflow - Bootstrap](https://stackoverflow.com/questions/tagged/bootstrap)
- [Reddit r/bootstrap](https://www.reddit.com/r/bootstrap/)

---

## 💡 Consejos para Principiantes

1. **Empieza con CDN**: Es la forma más rápida de comenzar.
2. **Aprende el Grid**: Es la base de Bootstrap.
3. **Usa utilidades**: Ahorra tiempo con clases de spacing.
4. **Personaliza con Sass**: Para proyectos profesionales.
5. **Verifica accesibilidad**: No todos usan mouse.

---

## ⚠️ Mejores Prácticas

### Rendimiento

- Usa solo los componentes que necesitas
- Considera PurgeCSS para producción
- Optimiza imágenes

### Accesibilidad

- Usa atributos ARIA cuando sea necesario
- Mantén contraste de colores adecuado
- Asegura navegación por teclado

### Código

- Sigue la documentación oficial
- Usa nombres de clases semánticos
- Mantén HTML limpio

---

## 🧪 Ejercicios Prácticos

### Nivel Básico

1. Crea un navbar responsive
2. Diseña una landing page simple
3. Implementa un formulario de contacto

### Nivel Intermedio

1. Crea un dashboard con sidebar
2. Implementa un carrusel de imágenes
3. Diseña una página de productos

### Nivel Avanzado

1. Crea un tema personalizado con Sass
2. Implementa dark mode toggle
3. Desarrolla una plantilla completa

---

## 👨‍💻 Desarrollado por Isaac Esteban Haro Torres

**Ingeniero en Sistemas · Full Stack · Automatización · Data**

- 📧 Email: zackharo1@gmail.com
- 📱 WhatsApp: 098805517
- 💻 GitHub: https://github.com/ieharo1
- 🌐 Portafolio: https://ieharo1.github.io/portafolio-isaac.haro/

---

© 2026 Isaac Esteban Haro Torres - Todos los derechos reservados.
