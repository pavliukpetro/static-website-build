# Static Website Build

This is a builder for creating simple static websites without JS frameworks.
The builder is based on npm scripts.

It uses:
- HTML with partials
- SCSS with linting and autoprefixer
- JavaScript with webpack using babel and linting
- browser-sync

## Folders structure
<pre>
static-website-build/
└── src
    ├── images
    ├── js
    ├── modules
    └── scss
    index.html
</pre>

## Demo

[Github Page](https://pavliukpetro.github.io/static-website-build/)

## Getting Started

1. Install dependencies
```
npm install
```

2. Build resources
```
npm run build
```

3. Watch for changes
```
npm run watch
```

## License
[MIT](https://choosealicense.com/licenses/mit/)

---

*created by [Petro Pavliuk](https://github.com/pavliukpetro)*
