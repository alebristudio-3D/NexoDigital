# NexoDigital Web

Sitio web estático para **NexoDigital | Páginas Web y Presencia Digital**.

## Estructura

```txt
nexodigital-web/
├── index.html
├── css/
│   └── styles.css
├── assets/
│   ├── logo-nexodigital.png
│   └── hero-nexodigital.jpg
├── README.md
├── .gitignore
└── .nojekyll
```

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube todos los archivos de esta carpeta al repositorio.
3. Ve a **Settings > Pages**.
4. En **Build and deployment**, selecciona:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Guarda los cambios.
6. GitHub generará una URL pública para el sitio.

## Personalización pendiente

Busca y reemplaza el WhatsApp provisional:

```txt
5212220000000
```

por el número real en formato internacional, por ejemplo:

```txt
5212221234567
```

## Imágenes

Las imágenes están en la carpeta `assets/` y ya están conectadas desde `css/styles.css`:

```css
--nd-logo:url("../assets/logo-nexodigital.png");
--nd-hero-img:url("../assets/hero-nexodigital.jpg");
```

El logo incluido es la versión blanca actualizada, ideal para el modo oscuro.
