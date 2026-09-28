# Examen Anexo 04 · Inducción y orientación básica

Evaluación del Área de Seguridad basada en el D.S. 024-2016-EM y su modificatoria D.S. 023-2017-EM.

- `index.html`: el examen (100 preguntas, 20 por colaborador, sin repetir).
- `apps-script/Codigo.gs`: código para pegar en Google Apps Script (sorteo sin repetir y guardado de resultados).
- `datos/preguntas_anexo04.csv`: las 100 preguntas para importar a tu Google Sheets.

## Configuración
Edita `CONFIG` dentro de `index.html`:
- `WEBAPP_URL`: URL `/exec` de tu Apps Script.
- `PREGUNTAS_CSV_URL` (opcional): enlace CSV publicado de tu pestaña PREGUNTAS.
- `TOTAL` y `NOTA_MINIMA`: preguntas por examen y nota aprobatoria.

## Publicar con GitHub Pages
Settings > Pages > Deploy from a branch > `main` / `(root)`.
