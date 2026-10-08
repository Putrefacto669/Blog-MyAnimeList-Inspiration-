# Blog de reseñas de anime · demos de estilo

Tres propuestas de diseño para el mismo blog, más una página de inicio para escoger.

| Archivo | Estilo |
|---|---|
| `index.html` | Inicio: presenta los tres estilos |
| `hanko.html` | **Hanko**: manga en papel, tinta y sello rojo |
| `neon.html` | **Neon Gakuen**: club nocturno, neón sobre índigo |
| `sora.html` | **Sora List**: base de datos limpia tipo MyAnimeList |

## Cómo verlo
Es HTML estático, sin build. Se puede abrir `index.html` directo o publicarlo en GitHub Pages / Cloudflare Pages apuntando a la raíz del repo.

## Funciones (iguales en los tres)
- Botón **Entrar como admin** (demo, sin contraseña) para publicar reseñas con nota, estrellas y texto.
- El admin decide el Anime del día, el Top semanal, el Top mensual y el Top histórico (con orden).
- Los visitantes comentan cada anime con estrellas opcionales.
- El admin borra comentarios o quita solo las estrellas de un comentario.

## Limitaciones de la demo
- Los datos viven en el `localStorage` de cada navegador; no se comparten entre usuarios.
- El modo admin es un interruptor. La versión real necesita login y una base de datos (p. ej. Supabase o Cloudflare D1).
- **Restablecer demo** (en el pie) vuelve a los datos de ejemplo.
