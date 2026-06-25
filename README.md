# El cristal que no supe sostener

Landing page estática para promocionar el libro **El cristal que no supe sostener**, de **Emilio Sebastián Franco**.

El sitio está preparado para publicarse gratis en GitHub Pages e incluye HTML semántico, CSS responsive, imágenes optimizadas en WebP, metadatos SEO, Open Graph, Twitter Card, `robots.txt`, `sitemap.xml` y datos estructurados JSON-LD con `Book` y `FAQPage`.

## Archivos principales

- `index.html`: página principal de la landing.
- `styles.css`: estilos visuales y responsive.
- `cover.webp`: portada optimizada para web.
- `author.webp`: foto del autor optimizada para web.
- `favicon.png`: favicon del sitio.
- `robots.txt`: permite la indexación.
- `sitemap.xml`: sitemap con la URL pública final.

## Cómo publicarlo en GitHub Pages

1. Subí todos los archivos de esta carpeta al repositorio `libro`.
2. En GitHub, entrá a **Settings**.
3. Abrí **Pages**.
4. En **Build and deployment**, elegí la rama principal, normalmente `main`.
5. Seleccioná la carpeta raíz `/`.
6. Guardá los cambios.

La URL esperada del sitio es:

```text
https://francoliterato.github.io/libro/
```

## Cómo cambiar enlaces de compra

En `index.html`, buscá los enlaces actuales:

```text
https://www.amazon.com/dp/B0GX2WQNB6
https://play.google.com/store/books/details/Emilio_Sebasti%C3%A1n_Franco_El_cristal_que_no_supe_sos?id=vursEQAAQBAJ
```

Actualizalos en:

- Botones del hero.
- Sección "Dónde comprar".
- Footer.
- JSON-LD `Book`, dentro de `sameAs` y `offers`.

## Cómo actualizar el sitemap

Si cambia la URL pública, editá `sitemap.xml` y reemplazá:

```text
https://francoliterato.github.io/libro/
```

También actualizá en `index.html`:

- `link rel="canonical"`.
- `og:url`.
- URLs absolutas de `og:image`, `twitter:image` y JSON-LD.

Si solo actualizás contenido, cambiá la fecha de `lastmod` en `sitemap.xml`.

## Cómo indexarlo en Google Search Console

1. Entrá en Google Search Console.
2. Agregá la propiedad con la URL:

```text
https://francoliterato.github.io/libro/
```

3. En **Sitemaps**, enviá:

```text
https://francoliterato.github.io/libro/sitemap.xml
```

4. Usá la herramienta de inspección de URL para solicitar indexación de la página principal.

## Notas SEO

El sitio está técnicamente preparado para indexación, pero Google puede tardar en rastrear e incorporar la página. El posicionamiento final depende de competencia, autoridad del dominio, enlaces externos, búsquedas reales y comportamiento de los usuarios.
