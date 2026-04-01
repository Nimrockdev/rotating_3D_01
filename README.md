# Rotating 3D Globe (HTML/CSS/JS)

Demo visual de un globo terráqueo wireframe en 3D, animado con `canvas` y JavaScript puro en CodeX.

## Características

- Renderizado de esfera 3D con líneas de latitud y longitud.
- Animación continua y suave de rotación (sin interacción requerida).
- Profundidad visual con trazos frontales/traseros y sombreado radial.
- Implementación ligera, sin dependencias externas.
- Preparado para despliegue automático en GitHub Pages.

## Estructura

- `index.html`: página principal con estilos y lógica de render.
- `.github/workflows/deploy-pages.yml`: workflow para desplegar en GitHub Pages.
- `.nojekyll`: desactiva el procesamiento Jekyll en Pages.

## Ejecución local

Puedes abrir `index.html` directamente en el navegador o servirlo localmente:

```bash
python3 -m http.server 8000
```

Luego visita: `http://localhost:8000`

## Publicación en GitHub Pages

1. Sube los cambios al repositorio remoto.
2. En GitHub, ve a **Settings → Pages**.
3. Selecciona **Source: GitHub Actions**.
4. Haz merge a `main`/`master` para disparar el deploy.

## Licencia

Uso libre para fines educativos y de demostración.
