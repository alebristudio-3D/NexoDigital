# NexoDigital Web

Sitio web estático para **NexoDigital | Páginas Web y Presencia Digital**.

## Estructura

```txt
nexodigital-web/
├── index.html
├── css/
│   └── styles.css
└── assets/
    ├── logo-nexodigital.png
    └── hero-nexodigital.jpg
```

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio nuevo en GitHub, por ejemplo: `nexodigital-web`.
2. Sube todos los archivos de esta carpeta.
3. En GitHub entra a **Settings > Pages**.
4. En **Build and deployment**, selecciona:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Guarda los cambios.

GitHub generará una URL como:

```txt
https://TU-USUARIO.github.io/nexodigital-web/
```

## Comandos sugeridos

```bash
git init
git add .
git commit -m "Sitio inicial NexoDigital"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/nexodigital-web.git
git push -u origin main
```

## Pendientes antes de publicar

- Cambiar el WhatsApp provisional `5212220000000` por el número real.
- Ajustar precios si se requiere.
- Agregar dominio personalizado si aplica.
