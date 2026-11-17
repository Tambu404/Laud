# Tortuga laúd: atrapá medusas

Juego web educativo para celulares y computadora. La tortuga laúd se mueve de lado a lado, atrapa medusas celestes y esquiva las bolsas de plástico, que en el mar suelen confundirse con medusas.

## Cómo se juega

- Deslizá el dedo (o el cursor) para mover la tortuga.
- Cada medusa suma 10 puntos; 5 seguidas suben el combo (hasta ×5).
- Cada bolsa que tocás te quita una vida (tenés 3).
- Cada 10 medusas subís de nivel y todo cae más rápido.

## Archivos

```
index.html   ← todo el juego (HTML + CSS + JavaScript)
Logo.png     ← logo del pie de página
README.md
```

No necesita instalación ni dependencias.

## Probarlo en tu compu

Abrí `index.html` con el navegador (doble clic).

## Publicarlo con GitHub Pages

1. Subí los tres archivos a un repositorio nuevo en GitHub.
2. Entrá a **Settings → Pages**.
3. En **Build and deployment**, elegí **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
4. Guardá. En un minuto el juego queda en `https://TU_USUARIO.github.io/NOMBRE_DEL_REPO/`.

## Personalizar

Al principio del `<script>` de `index.html` está el bloque `CONFIG`:

```js
const CONFIG={
  logo:'Logo.png',
  text:'Texto del pie de página',
  links:[{t:'Aquamarina.org',u:'https://aquamarina.org/'}],
  donateUrl:'https://…'
};
```

Ahí se cambian el logo, el texto, los links y el botón de donación.
