# Canal de Descubre

`feed.json` es el contenido de la sección **Descubre** de Mi Semana Escolar (desde la versión 2.1.0).
La app lo descarga como máximo cada 3 horas; si no hay internet, usa la copia incluida en la APK.

- `notes`: noticias (`id`, `category`, `title`, `body`, `source`, `url` https, `date`, opcional `cover` https, `videoId` de YouTube, `question`, `emoji`, `until` para ocultarla después de esa fecha).
- `facts`: datos «¿Sabías que…?» (`emoji`, `category`, `text`).
- Cambia `updated` en cada edición.

Criterios: contenido apto para un estudiante de 12–13 años, resúmenes propios en español (sin copiar textos), enlaces a la fuente original.
