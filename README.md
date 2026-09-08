# calytek-planta (código)

PWA de control de recepción de la planta CALYTEK de MINSA ENERGY. Este directorio es un repo
propio (público, `MINSA-CAPTURA/minsa-calytek-planta`, servido por GitHub Pages); la documentación, el plan y el setup viven en el acervo del holding
(`proyectos/calytek-planta-app/docs/`).

```bash
npm test                 # node: reglas de la puerta + service worker
node servidor-local.js   # http://localhost:8080/
```

Archivos: `index.html` (pantallas) · `app.js` (flujo) · `reglas.js` (compuerta, folios, tolerancia —
puras) · `graph.js` (listas y biblioteca por Microsoft Graph) · `imagen.js` (foto del indicador) ·
`esquema.json` (las 7 listas) · `config.js` (ids públicos, sin secretos) · `sw.js`.
