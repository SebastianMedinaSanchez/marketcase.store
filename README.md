# Marketcase.store

Repositorio para el sitio web de **marketcase.store** - Plataforma de vitrinas digitales profesionales.

## Estructura del Proyecto

```
marketcase.store/
├── README.md                          # Documentación del proyecto
├── netlify.toml                       # Configuración de Netlify
├── index.html                         # Página principal
├── home.html                          # Página de inicio
├── blog.html                          # Página de blog
├── contacto.html                      # Página de contacto
├── servicios.html                     # Página de servicios
├── about.html                         # Página acerca de
├── portafolio.html                    # Página de portafolio
├── script.js                          # JavaScript principal
│
├── styles/
│   ├── variables.css                  # Variables y colores globales
│   ├── style.css                      # Estilos principales
│   └── components/
│       ├── navbar.css                 # Estilos de navegación
│       ├── footer.css                 # Estilos de pie de página
│       ├── buttons.css                # Estilos de botones
│       ├── cards.css                  # Estilos de tarjetas
│       └── forms.css                  # Estilos de formularios
│
├── scripts/
│   ├── script.js                      # Script principal
│   └── modules/
│       ├── form-handler.js            # Manejador de formularios
│       ├── navbar.js                  # Funcionalidad de navegación
│       └── darkmode.js                # Toggle de modo oscuro
│
└── assets/
    ├── img/                           # Imágenes
    ├── icons/                         # Iconos
    └── fonts/                         # Fuentes personalizadas
```

## Características Principales

✅ **HTML Semántico**: Estructura mejorada con etiquetas HTML5 apropiadas
✅ **CSS Modular**: Estilos organizados en componentes reutilizables
✅ **Variables CSS**: Sistema de colores y espaciamiento global
✅ **Accesibilidad**: Mejoras ARIA y navegación por teclado
✅ **Responsivo**: Diseño adaptable a todos los dispositivos
✅ **SEO Optimizado**: Meta descripciones y Open Graph listos
✅ **JavaScript Modular**: Código organizado en módulos independientes

## Primeros Pasos

### Requisitos
- Navegador moderno (Chrome, Firefox, Safari, Edge)
- Editor de código (VS Code recomendado)
- Git para versión control

### Clonar el Repositorio

```bash
git clone https://github.com/SebastianMedinaSanchez/marketcase.store.git
cd marketcase.store
```

### Desarrollo Local

1. Abre cualquier archivo `.html` en tu navegador
2. O usa un servidor local como Live Server en VS Code

## Despliegue

El sitio está configurado para desplegar automáticamente en **Netlify**:

1. Conecta tu repositorio a Netlify
2. Netlify detectará automáticamente la configuración en `netlify.toml`
3. Los cambios en `main` se desplegarán automáticamente

## Estructura de Directorios

### Páginas HTML
Cada página mantiene la misma estructura semántica:
- `<header>` con navegación
- `<main>` con contenido principal
- `<footer>` con información de contacto y enlaces

### Estilos CSS
- `variables.css`: Define variables de color, espaciado y tipografía
- `components/`: Estilos modulares por componente
- Todos los componentes se importan en `style.css`

### JavaScript
- `script.js`: Punto de entrada y carga de módulos
- `modules/`: Funcionalidad modular y reutilizable
- Sin dependencias externas (vanilla JavaScript)

## Editar Contenido

### Agregar una Página Nueva

1. Crea un archivo `nombre.html` en la raíz
2. Copia la estructura de `index.html`
3. Modifica el contenido en `<main>`
4. Actualiza los enlaces de navegación en `<header>`

### Cambiar Colores y Branding

Edita `styles/variables.css`:

```css
:root {
  --color-primary: #2f80ed;      /* Color principal */
  --color-secondary: #56cc9d;    /* Color secundario */
  --color-dark: #1a1a2e;         /* Fondo oscuro */
  --color-accent: #ffe600;       /* Color de acento */
}
```

### Agregar Formularios

Cada formulario debe conectarse a un manejador en `scripts/modules/form-handler.js`

## Accesibilidad

El proyecto incluye mejoras de accesibilidad:
- Atributos `role` y `aria-label` en elementos interactivos
- Contraste de colores óptimo
- Navegación por teclado
- Etiquetas semánticas HTML5

## SEO

Cada página incluye:
- Meta descripción
- Open Graph (og:title, og:description, og:image)
- Estructura semántica
- URLs amigables

## Soporte y Contacto

📧 Email: info@marketcase.co
📱 Teléfono: +57 300 123 4567
🌐 Sitio Web: marketcase.store

## Contribuciones

1. Haz un fork del repositorio
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## Licencia

Este proyecto está bajo licencia MIT. Ver `LICENSE` para más detalles.

---

**Hecho con 💙 en Colombia**
