# Portfolio Cristian Ojeda - Backend Java Developer

## 🚀 Características
- Diseño responsive mobile-first
- Dark/Light mode toggle
- Sistema anti-spam para email
- Proyectos cargados dinámicamente
- Optimizado para Netlify

## ✏️ Personalización

### 1. Información Personal
Editar en `index.html`:
- Línea 10: `<title>Cristian Ojeda | Java Backend Developer</title>`
- Línea 248: `<a href="#" class="logo">Cristian<span>Ojeda</span></a>`
- Línea 269: `<h1 class="hero-title">Cristian Ojeda</h1>`

### 2. Proyectos
Editar en el `<script>` (línea ~420):
```javascript
const projectsData = [
  {
    title: "Tu Proyecto",
    subtitle: "Tecnología usada",
    description: "Descripción detallada",
    technologies: ["Java", "Spring Boot"],
    github: "https://github.com/tuusuario",
    status: "completed"
  }
];