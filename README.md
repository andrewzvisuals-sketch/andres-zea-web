# Andrés Zea — Portfolio Website

Portfolio personal de Andrés Zea, Video Editor & Motion Graphics Designer basado en Colombia.

## Estructura del proyecto

```
andres-zea-web/
├── index.html          ← Página principal (todo en un solo archivo)
└── assets/
    ├── ANDREW_1.jpg    ← Foto principal hero
    ├── Asset_1.png     ← Logo texto (fondo oscuro)
    ├── Asset_2.png     ← Logo texto (fondo claro)
    ├── Asset_4.png     ← Ícono diamante decorativo
    └── Asset_5.png     ← Logo circular "az"
```

## Cómo correrlo localmente

Abre `index.html` directamente en tu navegador — no necesita servidor ni dependencias.

O si tienes VS Code, instala la extensión **Live Server** y haz clic en "Go Live".

## Deploy en GitHub Pages

1. Sube esta carpeta a un repositorio en GitHub
2. Ve a **Settings → Pages**
3. En "Source" selecciona **main branch / root**
4. Tu sitio estará en `https://tu-usuario.github.io/andres-zea-web/`

## Personalización rápida

- **Colores**: Busca `:root` en el CSS, cambia `--amber: #F5A623`
- **Textos**: Edita directamente en el HTML
- **Foto hero**: Reemplaza `assets/ANDREW_1.jpg`
- **Proyectos**: Edita las `.work-card` en la sección `#work`
- **Links sociales**: Busca los botones `ig`, `yt`, `@` y agrega `href`

## Tecnologías

- HTML5 + CSS3 + Vanilla JS (sin frameworks)
- Fonts: Syne + DM Sans (Google Fonts)
- Totalmente responsive (mobile, tablet, desktop)
