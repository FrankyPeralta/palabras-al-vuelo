# Palabras al Vuelo

Juego corto de ortografía para primer grado: dictado en español y spelling en inglés. Funciona en el navegador y se instala como app en el celular. Después de la primera carga también funciona sin internet.

## Qué contiene

- `index.html`: portada para elegir la lista.
- `semana-8.html`: dictado de la semana 8 y spelling en inglés.
- `practica-bv-fry.html`: 46 palabras con b y v y la lista Fry.
- `manifest.webmanifest`, `sw.js` e `icons/`: lo que permite instalarla como app y usarla sin internet.

## Publicar en GitHub Pages

1. En github.com, crea un repositorio nuevo (por ejemplo `palabras-al-vuelo`) y márcalo como público.
2. Entra al repositorio, elige **Add file > Upload files** y arrastra todo el contenido de esta carpeta, incluida la carpeta `icons`. Confirma con **Commit changes**.
3. Ve a **Settings > Pages**. En **Source** elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`, y guarda.
4. Espera uno o dos minutos. La dirección queda como `https://TU-USUARIO.github.io/palabras-al-vuelo/`.

## Instalarla como app

- **iPhone o iPad:** abre la dirección en Safari, toca Compartir y elige **Añadir a pantalla de inicio**.
- **Android:** abre la dirección en Chrome, toca el menú de tres puntos y elige **Instalar app** o **Añadir a pantalla de inicio**.

## Voz

La app usa la voz del dispositivo. En inglés busca una voz británica (en-GB) y lee la oración completa. En "Para mamá o papá" se ve qué voz se está usando y hay botones para probarla. Si el dispositivo no tiene voz británica, hay que instalarla en los ajustes de voz del sistema.

## Cambiar las palabras

Dentro de cada lista, entra a **Para mamá o papá**. Ahí se escribe el nombre del niño, las palabras y las oraciones. Se guarda solo en ese dispositivo.

## Actualizar el código

Si cambias un archivo en GitHub, la app descarga la versión nueva la siguiente vez que se abre con internet. Si algún día no se actualiza, cambia el número de `CACHE` en `sw.js` (por ejemplo de `palabras-v1` a `palabras-v2`).

## Privacidad

El nombre del niño, las estrellas y el progreso se guardan solo en el navegador de cada dispositivo. No se envían a GitHub ni a ningún servidor. El nombre que viene por defecto es genérico.
