# lives-probador-celular
Herramienta auxiliar de LIVES, con su logo (no es del portal ni usa Supabase): página instalable (PWA) que muestra cualquier pantalla con el ancho real de un celular, para probar cómo se ve. Pegas el link, eliges modelo, giras, zoom. Se pueden ver hasta 3 pantallas a la vez (botones «＋ Agregar pantalla» y «− Quitar pantalla»); la 2 y la 3 pueden tener otro link (vacío = el de la primera) y su propio modelo. Solo guarda en el equipo el último link usado.
- Archivos: `index.html` (todo el código), `manifest.webmanifest`, `sw.js` (abre sin internet), `icons/`.
- Sin datos de la empresa. Reglas generales: repo lives-instrucciones.
- Límite: un sitio que prohíbe verse dentro de otra página sale en blanco; ahí se usa Chrome con F12 y Ctrl+Shift+M. No fuerza modo oscuro. Pruébalo solo en https (Pages), no en http.
