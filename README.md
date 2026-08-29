# Sitio web — Evidentia SpA

Sitio de una página para Evidentia, dirección científica externa para proyectos de salud.

## Estructura

```
evidentia-site/
├── index.html      # Contenido y estructura de las secciones
├── styles.css      # Sistema de diseño (colores, tipografía, layout)
├── script.js       # Contador de cifras animado + revelado al hacer scroll
├── NOTES.md         # Racional de negocio, neuromarketing y diseño
└── README.md         # Este archivo
```

## Cómo verlo

Abre `index.html` haciendo doble clic — se abre directo en el navegador. No necesita servidor ni build.

## Cómo seguir trabajando en VS Code

1. Descarga esta carpeta completa y ponla donde quieras tu proyecto (por ejemplo `~/proyectos/evidentia-site`).
2. Ábrela en VS Code: `Archivo → Abrir carpeta…`
3. Ya viene inicializada como repositorio Git local (`git log` para ver el primer commit).
4. Para subirla a GitHub:
   ```bash
   gh repo create evidentia-site --private --source=. --remote=origin
   git push -u origin main
   ```
   O crea el repo vacío desde github.com y luego:
   ```bash
   git remote add origin <URL-del-repo>
   git branch -M main
   git push -u origin main
   ```
5. Desde ahí, puedes seguir pidiéndome cambios usando Claude Code directamente en VS Code — ya tendré el historial y el contexto del proyecto en los archivos.

## Publicarlo (hosting)

Al ser HTML/CSS/JS estático, cualquiera de estas opciones funciona sin configuración adicional:
- **GitHub Pages** (gratis, directo desde el mismo repo)
- **Netlify** o **Vercel** (arrastrar la carpeta o conectar el repo)

## Próximos pasos sugeridos

- Decidir si se necesita una segunda página (ej. política de privacidad) si vas a captar correos.

## Estado de publicación

- Repo: https://github.com/AndresGFontaine/evidentia-site (público)
- Publicado con GitHub Pages, dominio propio conectado: https://www.evidentialabs.cl
- Correo de contacto: contacto@evidentialabs.cl
