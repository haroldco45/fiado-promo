# Fiado — página de promoción para tenderos

Página para promover el uso de **Fiado, cuaderno digital del tendero**
(https://fiado-cuadernodeltendero.netlify.app/) como valor agregado para las tiendas de barrio.

## Qué trae
- Presentación de la app con botón directo para abrirla.
- Calculadora: "¿Cuánta plata tiene en la calle?" con los datos de cada tienda.
- Comparación cuaderno vs. app, guía para instalarla en Android y iPhone.
- Afiche imprimible con código QR para el mostrador (botón "Imprimir afiche").
- Botón para reenviar la app a otro tendero por WhatsApp.
- Preguntas frecuentes, botón flotante de WhatsApp (311 770 0431).
- PWA: manifest.json, service worker e instalación.
- Vista previa para WhatsApp/Facebook (og-image.jpg, 1200×630).

## Archivos (todos en la raíz del repo)
```
index.html
og-image.jpg
manifest.json
sw.js
icon-192.png
icon-512.png
README.md
```

## Publicar
1. Cree el repo `haroldco45/fiado-promo` y suba todos los archivos a la raíz.
2. En Netlify: Add new site → Import from GitHub → `fiado-promo`.
3. En Site settings → Change site name, póngale `fiado-promo`,
   para que quede en https://fiado-promo.netlify.app/
4. Verifique que abra https://fiado-promo.netlify.app/og-image.jpg

Si usa otra dirección, cambie `https://fiado-promo.netlify.app/` en las
etiquetas `og:` y `twitter:` del `index.html` (buscar y reemplazar).

Para refrescar la vista previa en WhatsApp comparta el enlace con `?v=2`.

---
Desarrollada por **Vibras Positivas HM** — Derechos de Autor Reservados
