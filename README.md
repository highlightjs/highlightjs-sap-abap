[![npm version](https://badge.fury.io/js/highlightjs-sap-abap.svg)](https://badge.fury.io/js/highlightjs-sap-abap)

# highlightjs-sap-abap

SAP ABAP highlighting for highlight.js

## Build distributable

- install this repo in folder extra of [highlightjs](https://github.com/highlightjs/highlight.js)
- run the build tool from the main highlightjs folder:

```sh
npm run build-cdn
```

## Usage

Simply include the Highlight.js library in your webpage or Node app, then load this module.

### Static website or simple usage

Simply load the module after loading Highlight.js. This module is just a CDN build of the language, so it will register itself as the Javascript is loaded.

```html
<link rel="stylesheet" href="/path/to/styles/default.css">
<script src="/path/to/highlight.min.js"></script>
<script src="/path/to/highlightjs-sap-abap/dist/abap.min.js"></script>
<script type="text/javascript">
  hljs.highlightAll();
</script>
```

### Using directly from the jsDelivr CDN

```html
<link rel="stylesheet" href="//cdn.jsdelivr.net/gh/highlightjs/cdn-release/build/styles/default.min.css">
<script src="//cdn.jsdelivr.net/gh/highlightjs/cdn-release/build/highlight.min.js"></script>
<script src="https://cdn.jsdelivr.net/gh/highlightjs/highlightjs-sap-abap/src/abap.min.js"></script>
```

## License

MIT

## Maintainers

[@cassioiks](https://github.com/cassioiks), [@larshp](https://github.com/larshp)
