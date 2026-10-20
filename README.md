# HeartTrack · Soporte y privacidad

Páginas oficiales de soporte y privacidad de HeartTrack, una app para sensores Bluetooth de frecuencia cardíaca.

- Web: https://joshid.github.io/hearttrack-support/
- Soporte: https://joshid.github.io/hearttrack-support/support.html
- Privacidad: https://joshid.github.io/hearttrack-support/privacy.html

El contenido está en español y contiene ayuda y un resumen de privacidad en inglés.

## Publicación

GitHub Pages publica la raíz de la rama `main`. La web es HTML/CSS estático, no requiere dependencias ni compilación. `.nojekyll` evita el procesamiento con Jekyll. Los cambios guardados en `main` se publican automáticamente.

## Editar y revisar

Modifica `index.html`, `support.html`, `privacy.html` y `styles.css`. Los originales de los textos en español están en `content/` y deben mantenerse sincronizados con las páginas. Las rutas están preparadas para `/hearttrack-support/`.

Para una vista previa local, ejecuta `python3 scripts/preview.py` y abre http://127.0.0.1:8766/hearttrack-support/.

Antes de subir cambios, ejecuta `python3 scripts/validate.py` para verificar enlaces y recursos locales.

Soporte: https://github.com/joshid/hearttrack-support/issues
