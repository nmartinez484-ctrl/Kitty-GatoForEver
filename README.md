# Invitación: Karina & Nelson

Pequeña página web de invitación para la boda de Karina y Nelson. Incluye contador regresivo, texto informativo y control de música de fondo.

## Archivos incluidos
- `index.html` — archivo único con HTML, CSS y JavaScript embebidos.
- (Opcional) archivo de audio externo — añadí el enlace público de Google Drive como fuente.

## Personalización rápida
1. La fecha/hora en `index.html` ya está fijada al 20-12-2025 18:00 CL (UTC-03:00).
2. Si quieres cambiar la canción reemplaza la URL en el elemento `<audio>` por otra URL pública.
3. Modifica textos, dirección o emojis directamente en el HTML.

## Probar localmente
En la carpeta con `index.html` ejecuta:
- Python 3: `python -m http.server 8000` -> abrir http://localhost:8000
- O con Node: `npx http-server . -p 8000`

## Publicar en GitHub Pages
Opción A — publicar desde la rama `main`:
```bash
git clone https://github.com/nmartinez484-ctrl/Kitty-GatoForEver.git
cd Kitty-GatoForEver
# Copia index.html (y audio si aplica) aquí
git add .
git commit -m "Add wedding invitation site (Karina & Nelson) and audio"
git branch -M main
git push -u origin main
```
Opción B — usar branch `gh-pages`:
```bash
git checkout -b gh-pages
git add .
git commit -m "Add wedding invitation site (gh-pages)"
git push -u origin gh-pages
```

## Notas
- El botón de audio requiere interacción del usuario.
- El contador usa `role="timer"` y `aria-live` para lectores de pantalla.
