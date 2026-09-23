Calculadora de Apps SST · Good Solutions
Sitio estático (un solo `index.html` + el logo). No necesita build ni dependencias.
Archivos
`index.html`: la página completa (estilos y lógica incluidos).
`gs-logo.png`: logo de Good Solutions.
`og-image.jpg`: imagen que aparece al compartir el link por WhatsApp o redes.
Deploy en Vercel desde GitHub
Crea un repositorio en GitHub y sube estos archivos a la raíz.
En Vercel: Add New… → Project → Import el repositorio.
Framework Preset: Other. Deja vacíos Build Command y Output Directory.
Deploy. Cada `git push` a la rama principal vuelve a publicar.
Ajustar precios
Al final de `index.html`, en el bloque `Configuración`, están la tarifa (`TARIFA_USD`), el tipo de cambio (`TIPO_CAMBIO`), el colchón (`AJUSTE`), el número de WhatsApp (`WHATSAPP`) y los tokens de cada funcionalidad (`GRUPOS`).
Vista previa en WhatsApp
El `index.html` apunta a `https://cotiza.goodsolutions.pe`. Si usas otro dominio, reemplázalo en las líneas `og:url`, `og:image` y `og:image:secure_url` del `<head>`.
WhatsApp guarda la vista previa en caché: si compartiste el link antes de subir la imagen, prueba agregando `?v=2` al final del link.
