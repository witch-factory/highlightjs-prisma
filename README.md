# Prisma Schema language grammar for [highlight.js](https://highlightjs.org/)

Prisma is an open-source ORM for Node.js and TypeScript. This module provides syntax highlighting for [Prisma schema](https://www.prisma.io/docs/orm/prisma-schema) files using Highlight.js.

## Usage

Simply include the Highlight.js library in your webpage or Node app, then load this module.

### Static website or simple usage

```html
<script type="text/javascript" src="/path/to/highlight.min.js"></script>
<script type="text/javascript" charset="UTF-8"
  src="/path/to/highlightjs-prisma/dist/prisma.min.js"></script>
<script type="text/javascript">
  hljs.highlightAll();
</script>
```

### With Node or another build system

If you're using Node / Webpack / Rollup / Browserify, etc, simply require the language module, then register it with Highlight.js.

```javascript
var hljs = require('highlight.js');
var hljsPrisma = require('highlightjs-prisma');

hljs.registerLanguage('prisma', hljsPrisma);
hljs.highlightAll();
```

## License

Highlight.js prisma is released under the MIT License. See LICENSE file for details.

### Author

SungHyun Kim <soakdma37@gmail.com>

## Links

- The official site for the Highlight.js library is <https://highlightjs.org/>.
- The Highlight.js GitHub project: <https://github.com/highlightjs/highlight.js>
- Prisma official site: <https://www.prisma.io/>