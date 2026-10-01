# 🍎 Sorpresa de cumpleaños para Miss Lulú

| Archivo | Para qué sirve |
|---|---|
| `tarjeta-imprimir.png` | La tarjeta en alta resolución, lista para imprimir |
| `tarjeta.png` | La misma tarjeta en tamaño normal (con esta se genera el archivo de RA) |
| `index.html` | La página de realidad aumentada |
| `tarjeta.svg` | La tarjeta editable (por si quieres cambiar algo) |

## Paso 1: generar `tarjeta.mind` (1 minuto)
1. Entra a https://hiukim.github.io/mind-ar-js-doc/tools/compile
2. Arrastra `tarjeta.png` y presiona **Start**.
3. Cuando termine, presiona **Download** y guarda el archivo como `tarjeta.mind` en esta misma carpeta.

## Paso 2: publicar la página (gratis y con https, que la cámara necesita)
**Opción fácil: Netlify Drop**
1. Entra a https://app.netlify.com/drop (puedes entrar con tu cuenta de Google).
2. Arrastra **toda la carpeta** `regalo-miss-lulu`.
3. Te dará una liga como `https://algo-bonito.netlify.app`. En la configuración del sitio puedes cambiarle el nombre, por ejemplo `cumple-miss-lulu`.

## Paso 3: código QR
1. Genera un QR con la liga (por ejemplo en https://www.qr-code-generator.com o desde Chrome: menú ⋮ → Compartir → Crear código QR).
2. Pégalo en la parte de atrás de la tarjeta o en un papelito junto al regalo.

## Paso 4: imprimir y probar
- Imprime `tarjeta-imprimir.png` en papel mate (el brillante refleja la luz y le cuesta reconocerla); unos 10 × 14 cm está perfecto.
- Abre la liga en tu celular, toca **¡Abrir sorpresa!**, da permiso a la cámara y apunta a la tarjeta.
- Sube el volumen: suena "Happy Birthday" con notitas 🎶

## Ver la animación sin cámara
Abre la liga con `#demo` al final (por ejemplo `https://cumple-miss-lulu.netlify.app/#demo`) y toca la pantalla para repetirla.
