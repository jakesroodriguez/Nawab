# Nawab Kebab & Tacos

Sitio web estático para Nawab Kebab & Tacos (Madrid).

## Estructura

- `frontend/index.html` — Página principal (Tailwind CSS vía CDN)

## Desarrollo local

Abre `frontend/index.html` en el navegador o sirve la carpeta `frontend` con cualquier servidor estático.

## Vercel

El proyecto incluye `vercel.json` con `outputDirectory: "frontend"`. En el dashboard de Vercel, usa **Framework Preset: Other** y deja que el repo aplique la configuración. Tras un redeploy, la raíz `/` debe servir `index.html`.
