# Sanbla Group — Sitio web (landings de Sanbla Consultoría)

Sitio estático. Sin compilación. Sirve los HTML directamente.

## Archivos principales

| Archivo | Descripción |
|---|---|
| `Comparador Sanbla Group.html` | Hub de entrada — enlaza a todas las landings |
| `sg-home-v1.html` | Home consultoría — estilo v2 Finance |
| `sg-home-v2.html` | Home consultoría — estilo Figma |
| `sg-concurso-v2.html` | Cerrar mi empresa bien |
| `sg-contacto-v2.html` | Contacto |
| `sg-articulo-v2.html` | Caso real / artículo |
| `sg-decisiones-reales-v2.html` | Hub decisiones reales |
| `sg-sobre-javier-v2.html` | Sobre Javier Sánchez |
| `sg-sobre-nosotros-v2.html` | Sobre nosotros |
| `sg-detalles-empresa-v2.html` | Detalle empresa SRV-BCN-001 |
| `sg-catalogo-v2.html` | Catálogo de empresas |
| `sg-vender-empresa-v2.html` | Vender mi empresa |

## Assets compartidos (carpeta `sanbla/`)

- `sanbla/styles-v2.css` — hoja de estilos
- `sanbla/premium.js` — interacciones (FAQ, scroll reveal, count-up)
- `sanbla/image-slot.js` — huecos de imagen arrastrables

## Publicar en GitHub Pages

1. Crea un repo nuevo en github.com (público).
2. Sube **todos** los archivos: los `sg-*.html`, el `Comparador Sanbla Group.html` y la carpeta `sanbla/` completa.
3. Settings → Pages → Source: rama `main` / carpeta `/root` → Save.
4. URL: `https://<usuario>.github.io/<repo>/Comparador%20Sanbla%20Group.html`

## Notas

- Las **imágenes** son huecos arrastrables (image-slot). En producción, sustitúyelas por `<img src="...">`.
- Fuentes: **Newsreader + Hanken Grotesk + Geist Mono** (Google Fonts, CDN).
- Cada `sg-` page tiene navegación interna entre las demás páginas del mismo grupo.
