# DT Desarrollo Web · página de contacto

Sitio estático (un solo `index.html` + la carpeta `img/`), listo para GitHub Pages. No necesita instalar nada.

## Publicar en GitHub Pages (gratis)

1. En https://github.com crea un repositorio **público**:
   - `dt-desarrollo-web` → la dirección será `https://TU-USUARIO.github.io/dt-desarrollo-web/`
   - o `TU-USUARIO.github.io` → la dirección será `https://TU-USUARIO.github.io/` (más corta).
2. En el repositorio: **Add file › Upload files**. Arrastra `index.html` y la carpeta `img` (con `david-taday.jpg` y `compartir.jpg`). Pulsa **Commit changes**.
3. **Settings › Pages** › Source: **Deploy from a branch** › Branch: `main` / `(root)` › **Save**.
4. En 1 o 2 minutos la página está en línea (la dirección aparece en la misma pantalla).

## Después de publicar

- **Vista previa al compartir el enlace** (WhatsApp, Facebook): en `index.html`, cambia
  `<meta property="og:image" content="img/compartir.jpg">` por la dirección completa,
  por ejemplo `https://TU-USUARIO.github.io/dt-desarrollo-web/img/compartir.jpg`.
- **Enlace desde Conde Mosca:** en el proyecto de la librería, `public/js/config.js` › `desarrollador.url`,
  pega la dirección de esta página y vuelve a publicar la librería.
- **Dominio propio (opcional):** si compras, por ejemplo, `dtdesarrolloweb.com`, en Settings › Pages › Custom domain.

## Qué editar

- WhatsApp: `593984775507` (aparece en varios enlaces `wa.me/…`) y el texto `098 477 5507`.
- Correo: `david_alext02@hotmail.com`.
- Precio: «desde $80» aparece en la portada y en la tarjeta de Página web informativa.
- Foto: reemplaza `img/david-taday.jpg` (vertical, unos 760 × 1145 px).

## Pestañas

La página se ve por pestañas: Inicio, Servicios, Cómo trabajamos, Fundador y Contacto (en celular, en el botón «Menú»).
Cada pestaña tiene su propia dirección (`…/#servicios`, `…/#contacto`), así que se puede compartir directo, por ejemplo
el enlace a Contacto. Para agregar una pestaña: crea otra `<section id="nombre">` dentro de `<main>` y su enlace en `<nav class="pestanas">`.
