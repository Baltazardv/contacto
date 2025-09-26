# 🌟 Página de Perfiles Profesionales

Una página web moderna y elegante para promocionar perfiles profesionales de GitHub y LinkedIn con efectos visuales impresionantes y funcionalidad interactiva.

## ✨ Vista Previa

Una landing page minimalista con diseño glassmorphism, efectos 3D y animaciones suaves que presenta de manera profesional los enlaces a perfiles de redes sociales.

## 🚀 Características

### Diseño Visual
- **Glassmorphism** - Efectos de vidrio esmerilado con transparencias
- **Gradientes vibrantes** - Colores dinámicos y atractivos
- **Animaciones CSS** - Transiciones suaves y efectos hover
- **Efectos 3D** - Interacción con el movimiento del mouse
- **Partículas flotantes** - Elementos animados de fondo

### Funcionalidad
- **Enlaces directos** - Acceso rápido a perfiles de GitHub y LinkedIn
- **Botones de copia** - Copia enlaces al portapapeles con un clic
- **Efectos de confirmación** - Feedback visual al copiar enlaces
- **Diseño responsivo** - Optimizado para desktop, tablet y móvil
- **Accesibilidad** - Navegación por teclado y lectores de pantalla

### Tecnologías
- **HTML5** - Estructura semántica
- **CSS3** - Animaciones, gradientes y efectos modernos
- **JavaScript vanilla** - Interactividad sin dependencias
- **Responsive Design** - Adaptable a cualquier dispositivo

## 📱 Compatibilidad

- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- ✅ Dispositivos móviles (iOS/Android)

## 🛠️ Instalación y Uso

### Opción 1: Descarga Directa
```bash
# Clonar el repositorio
git clone https://github.com/Baltazardv/perfil-profesional.git

# Navegar al directorio
cd perfil-profesional

# Abrir en navegador
open index.html
```

### Opción 2: Servidor Local
```bash
# Con Python
python -m http.server 8000

# Con Node.js (http-server)
npx http-server

# Con PHP
php -S localhost:8000
```

### Opción 3: Deploy Directo
Sube el archivo `index.html` a cualquier hosting web:
- GitHub Pages
- Netlify
- Vercel
- Hosting tradicional

## ⚙️ Personalización

### Cambiar Enlaces
Edita las URLs en el archivo HTML:
```html
<!-- GitHub -->
<a href="TU_GITHUB_URL" target="_blank">

<!-- LinkedIn -->
<a href="TU_LINKEDIN_URL" target="_blank">

<!-- Enlaces copiables -->
<input type="text" value="TU_GITHUB_URL" readonly>
<input type="text" value="TU_LINKEDIN_URL" readonly>
```

### Personalizar Información
```html
<!-- Cambiar nombre -->
<h1 class="profile-name">Tu Nombre</h1>

<!-- Cambiar descripción -->
<p class="profile-subtitle">Tu Título Profesional</p>
```

### Modificar Colores
```css
/* Gradiente principal */
background: linear-gradient(135deg, #TU_COLOR1 0%, #TU_COLOR2 100%);

/* Colores de tarjetas */
.github-card:hover {
    border-color: #TU_COLOR_GITHUB;
}

.linkedin-card:hover {
    border-color: #TU_COLOR_LINKEDIN;
}
```

## 📁 Estructura del Proyecto

```
perfil-profesional/
│
├── index.html          # Página principal
├── README.md           # Documentación
└── assets/            # (opcional)
    ├── images/        # Imágenes personalizadas
    └── styles/        # CSS adicional
```

## 🎨 Características Técnicas

### Animaciones CSS
- Rotación de elementos de fondo
- Efectos de hover con transforms 3D
- Transiciones suaves con cubic-bezier
- Animaciones de partículas flotantes

### JavaScript Interactivo
- Seguimiento del mouse en 3D
- Función de copia al portapapeles
- Generación dinámica de partículas
- Efectos de confirmación visual

### Responsive Design
- Mobile-first approach
- Breakpoints optimizados
- Flexbox para layouts
- Media queries específicas

## 🔧 Funcionalidades Avanzadas

### Copia al Portapapeles
```javascript
// Función con fallback para compatibilidad
function copyToClipboard(inputId) {
    // Implementación con execCommand y Clipboard API
}
```

### Efectos 3D
```javascript
// Seguimiento del mouse para rotación 3D
document.addEventListener('mousemove', (e) => {
    // Cálculo de rotación basado en posición del mouse
});
```

## 📊 Optimización

- **Peso total**: < 50KB
- **Tiempo de carga**: < 1 segundo
- **Sin dependencias externas**
- **Código minificable**
- **SEO friendly**

## 🌐 Demo en Vivo

Puedes ver una demo en vivo en: [Tu URL de demo]

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para cambios importantes:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`)
3. Commit tus cambios (`git commit -m 'Añadir nueva funcionalidad'`)
4. Push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

## 📝 Changelog

### v1.0.0 (2025-09-26)
- ✨ Lanzamiento inicial
- 🎨 Diseño glassmorphism
- 📱 Responsive design
- 🔗 Funcionalidad de copia de enlaces
- ✨ Efectos 3D y animaciones

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver archivo `LICENSE` para más detalles.

## 👤 Autor

**Baltazar Dimayuga**
- GitHub: [@Baltazardv](https://github.com/Baltazardv)
- LinkedIn: [baltazar-dimayuga](https://www.linkedin.com/in/baltazar-dimayuga/)

## 🙏 Agradecimientos

- Inspiración en diseños modernos de glassmorphism
- Efectos CSS de la comunidad de desarrolladores
- Iconos SVG de las plataformas oficiales

---

⭐ **¡Si te gusta este proyecto, dale una estrella!** ⭐
