# Contenido de la web de Angels & Demons Nails

Aquí viven **solo** los textos, precios, reseñas y fotos de https://angelsdemonsnails.com.
Se editan desde el panel (Pages CMS); no hace falta tocar este repositorio a mano.

- La web (`raulbr90/angels-demons-web`, privado) lee este contenido al publicarse: copia
  únicamente los archivos de `src/data/*.json` de la lista y las imágenes de `src/assets/fotos`
  (jpg, jpeg, png, webp). Cualquier otro archivo se ignora.
- Todo pasa por los tests y la auditoría de la web antes de publicarse: un dato mal escrito
  no rompe la web, simplemente no se publica y sigue la versión anterior.
- Cada 20 minutos (de día) se comprueba si hay cambios y, si los hay, se publican.

**Es un repositorio público**: todo lo que hay aquí ya es visible en la web. Antes de subir
una foto hecha con el móvil, conviene que no lleve la ubicación (desactivar la ubicación de la
cámara o pasarla antes por WhatsApp, que la elimina).

`.pages.yml` es una copia de la de la web: si cambian los campos, se actualizan las dos.
