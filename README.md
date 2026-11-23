# Dr. Grandel · Web principal para profesionales (www.dr-grandel.es)

Página de entrada de Dr. Grandel España para centros de estética: portada, novedades (Timeless, Ampoule Selection y Pro Collagen, cada una enlazada a su landing B2B), testimonios en vídeo, tour activo, marca alemana, Dr. Grandel en España y contacto.

## Dónde se ve
- Provisional (solo para el equipo): https://jose-bti-azp.github.io/drg-prof/ (GitHub Pages desde `main`, sin dominio propio, con `noindex`).
- Definitivo: www.dr-grandel.es. Al pasar al dominio: añadir CNAME, cambiar canonical y og (`og:url`, `og:image`) a www.dr-grandel.es y quitar `<meta name="robots" content="noindex">`.

## Ramas
- `main`: lo que se publica. Solo la actualiza Claude cuando Jose lo pide, con doble confirmación.
- `beta`: trabajo del equipo (Jose, colaboradoras, diseñadora).

## Notas
- Sin cookies ni analítica; tipografías alojadas en el repo; funciona sin JavaScript.
- Vídeo de testimonios: horizontal en ordenador (ePhVZ0oYNvM) y vertical en móvil (Ab-gy8JOo00). Solo se conecta con YouTube (youtube-nocookie.com) al pulsar play.
- Bloque «TOUR ACTIVO» (comentado en el HTML): las fechas pasadas se atenúan solas y el bloque se oculta cuando pasa la última. Para un tour nuevo, cambiar textos, `data-date`, foto y enlace.
- Citas de testimonios: pendientes.
