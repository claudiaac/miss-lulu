# 🍎 Sorpresa de cumpleaños para Miss Lulú

**Página:** https://claudiaac.github.io/miss-lulu/
**Demo sin cámara:** https://claudiaac.github.io/miss-lulu/#demo

| Archivo | Para qué sirve |
|---|---|
| `tarjeta-para-imprimir.pdf` | Hoja carta lista para imprimir y doblar (frente + QR atrás) |
| `tarjeta-imprimir.png` | Solo el frente, en alta resolución |
| `qr.png` | Código QR que abre la página |
| `index.html` | La página de realidad aumentada |
| `tarjeta.mind` | El archivo con el que la cámara reconoce la tarjeta |
| `tarjeta.png` / `tarjeta.svg` | La tarjeta en tamaño normal y editable |

## Cómo armar el regalo
1. Imprime `tarjeta-para-imprimir.pdf` en tamaño carta, **horizontal y al 100 %** (sin "ajustar a la página"). Mejor en papel opalina o cartulina mate: el brillante refleja la luz y a la cámara le cuesta reconocerla.
2. Recorta por la orilla y dobla por la línea punteada: al frente queda la manzanita y atrás el QR.

## Cómo se usa
1. Escanear el QR de atrás con el celular.
2. Tocar **¡Abrir sorpresa!** y dar permiso a la cámara.
3. Voltear la tarjeta y apuntar al frente (la manzanita): suena "Happy Birthday" 🎶 y salen globos, pastel y confeti.
4. Si no hay cámara, el enlace **"o verla sin cámara"** muestra la tarjeta animada en la pantalla.

> Si cambias `tarjeta.png`, hay que volver a generar `tarjeta.mind` en https://hiukim.github.io/mind-ar-js-doc/tools/compile
