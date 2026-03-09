Sitio espejo de Framer con único cambio: tipografía forzada a Helvetica.

Ruta principal:
- index.html

Rutas incluidas:
- contact.html
- projects/index.html
- projects/mienteme.html
- projects/mezcal-don-torres.html
- projects/coral-guayaberas.html
- projects/moveza.html
- projects/los-guitarrazos.html

Cambio aplicado:
- Se inyectó en cada HTML:
  <style id="helvetica-override">html, body, :where(*, *::before, *::after) { font-family: "Helvetica Neue", Helvetica, Arial, sans-serif !important; }</style>

No se modificó estructura ni animaciones de Framer.
