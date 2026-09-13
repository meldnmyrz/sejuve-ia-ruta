# Ruta IA SEJUVE

Guía del facilitador del programa de capacitación en inteligencia artificial de la Secretaría de la Juventud y la Niñez del Estado de Guerrero (SEJUVE). Sitio de tres pestañas: Programa, Cronograma y clases, Evaluación y normativa.

Sitio estático de un solo archivo (`index.html`), sin build ni dependencias. Cualquier hosting estático (Vercel, GitHub Pages, Netlify) lo sirve tal cual.

## Desarrollo local

Abre `index.html` directamente en el navegador, o sirve la carpeta con cualquier servidor estático:

```bash
npx serve .
```

## Despliegue en Vercel

1. Importa este repositorio en [vercel.com/new](https://vercel.com/new).
2. Framework preset: **Other**. No se necesita build command ni output directory (deja los valores por defecto o vacíos): Vercel sirve `index.html` desde la raíz automáticamente.
3. Cada `git push` a la rama principal vuelve a desplegar el sitio solo.
