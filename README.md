# docsify-for-offline

```bash
# konwersja do PDF
npx docsify-pdf-converter

# uruchomienie lokalnego serwera
npx docsify serve .
npx serve .
npx http-server -c-1 .
npx browser-sync start --server --no-ui --no-open --directory --serveStatic .
```

```html
<link rel="stylesheet" href="//localhost:3002/docsify/lib/themes/vue.css">
```

```html
<script src="//localhost:3002/docsify/lib/docsify.min.js"></script>
<script src="//localhost:3002/docsify/lib/plugins/search.min.js"></script>
<script src="//localhost:3002/docsify/lib/plugins/emoji.min.js"></script>
<script src="//localhost:3002/docsify/lib/plugins/zoom-image.min.js"></script>
<script src="//localhost:3002/docsify-copy-code/dist/docsify-copy-code.min.js"></script>
<script src="//localhost:3002/docsify-updated/src/time-updater.js"></script>
<script src="//localhost:3002/docsify-pagination/dist/docsify-pagination.min.js"></script>
<script src="//localhost:3002/prismjs/components/prism-json.min.js"></script>
<script src="//localhost:3002/prismjs/components/prism-bash.min.js"></script>
```
