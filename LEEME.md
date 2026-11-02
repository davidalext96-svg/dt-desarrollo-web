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
- Correo: `davidalext96@gmail.com`.
- Precio: «desde $80» aparece en la portada y en la tarjeta de Página web informativa.
- Foto: reemplaza `img/david-taday.jpg` (vertical, unos 760 × 1145 px).

- Planes: las tres tarjetas están en la sección `id="planes"`; la nota «Emito nota de venta, sin IVA adicional» está justo debajo.
- Preguntas frecuentes: cada pregunta es un bloque `<details><summary>Pregunta</summary><p>Respuesta</p></details>`.

## Diseño (versión 2, noviembre 2026)

Fondo azul noche, botones con degradado azul, tipografía DM Sans y botón flotante de WhatsApp.
La página se ve **por pestañas**, una sección a la vez: Inicio (portada, cifras y «Por qué importa») · Servicios · Planes ·
Cómo trabajamos · Fundador · Preguntas · Contacto. Cada pestaña tiene su dirección (`…/#planes`, `…/#contacto`) y termina con «Siguiente: …».
En celular, el menú se abre con el botón ☰. Sin JavaScript se ve todo seguido.

## Planes y precios (en la pestaña Planes)

| Plan | Desde | Renovación anual | Otros |
|---|---|---|---|
| Página web informativa | $80 | $35 | Lanzamiento $15 (solo la primera vez) |
| Página web con administración (más popular) | $250 | $80 | Informativa + formularios para contratar servicios, reportes y fotos del equipo con IA |
| Sistema de administración en línea | $700 | $200 | Incluye fotos del equipo con IA |
