# Calculadora de Apps SST · Good Solutions

Sitio estático (un solo `index.html` + el logo). No necesita build ni dependencias.

## Archivos
- `index.html`: la página completa (estilos y lógica incluidos).
- `gs-logo.png`: logo de Good Solutions.

## Deploy en Vercel desde GitHub
1. Crea un repositorio en GitHub y sube estos archivos a la raíz.
2. En Vercel: **Add New… → Project → Import** el repositorio.
3. Framework Preset: **Other**. Deja vacíos Build Command y Output Directory.
4. **Deploy**. Cada `git push` a la rama principal vuelve a publicar.

## Ajustar precios
Al final de `index.html`, en el bloque `Configuración`, están la tarifa (`TARIFA_USD`), el tipo de cambio (`TIPO_CAMBIO`), el colchón (`AJUSTE`), el número de WhatsApp (`WHATSAPP`) y los tokens de cada funcionalidad (`GRUPOS`).
