# Conejo-encuesta

Widget de cuestionario que genera un conejo pixelado a partir de tus respuestas.

## Cómo subirlo

1. Copia la carpeta `conejo-encuesta/` dentro de la sección de widgets de tu sitio, por ejemplo `widgets/conejo-encuesta/`.
2. Verifica que quede así:

   ```
   widgets/
   └── conejo-encuesta/
       ├── index.html
       └── README.md
   ```

3. Haz commit y push. Cuando GitHub Pages termine de publicar, el widget estará en:

   `https://TU-USUARIO.github.io/widgets/conejo-encuesta/`

## Notas

- Es un solo archivo HTML, sin dependencias locales. Solo carga la fuente Chewy y Nunito desde Google Fonts.
- Los conejos se guardan en `localStorage` del navegador, así que cada persona ve solo los suyos.
- Los botones para compartir usan la URL de la página donde esté publicada.
