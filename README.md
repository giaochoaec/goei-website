# goei-website

Sitio de **Gianella Ochoa Estética Integral** — https://giaochoa.ec

HTML estático servido por GitHub Pages. Sin compilación, sin JavaScript, sin cookies.

| Archivo | Para qué |
|---|---|
| `index.html` | Portada: nombre, eslogan, WhatsApp de la API y redes |
| `politica-privacidad.html` | Política de privacidad — la exigen las apps de Meta |
| `eliminacion-de-datos.html` | Instrucciones de eliminación de datos — campo obligatorio de las apps de Meta |
| `terminos-condiciones.html` | Condiciones de atención |
| `styles.css` | Colores y tipografía del Manual de Marca (verde `#939d93`, arena `#ecd6b4`, Montserrat) |
| `CNAME` | Dominio: `giaochoa.ec` |
| `whatsapp-ig/` | Dirección corta **giaochoa.ec/whatsapp-ig**: redirige a `wa.me` con el texto «Hola, les escribí por Instagram y quiero información». La usa la respuesta automática a mensajes directos de Instagram (escenario de Make `GOEI Redes - entrada`), porque en Instagram web el botón no se ve. Sin JavaScript: redirección por `meta refresh` y un enlace de respaldo |
| `robots.txt` | Abierto a todos los rastreadores: Meta revisa la política de privacidad con un rastreador automático |

## Reglas

- **Nunca** va en este repositorio nada de una paciente ni ninguna credencial. El repo es público.
- **La dirección exacta del local no se publica.** Se entrega al confirmar la cita (regla de seguridad del local).
- **El botón de WhatsApp va al número de la API** (+593 95 877 4101), con el texto prellenado «Hola, vengo del sitio web» para saber de dónde llegó la conversación. El texto no lleva emojis: así `wa.me` funciona igual en teléfono y en computadora.
- **Estas URLs las usan las apps de Meta.** Si se renombra o se mueve una página legal, hay que actualizar la URL en la configuración de cada app el mismo día.
