# Project layout

> *A complete game in one file*

This page is for developers who want to understand how the Lundby
project is laid out. It's the same layout the README documents, with
a few extra notes.

## The repository

```
.
├── index.html                  Entry point (loads the bundle + injects the save tooling)
├── manifest.webmanifest        PWA manifest (installable as an app)
├── favicon.png                 Browser tab icon
├── icon-192.png                PWA icon (192×192)
├── icon-512.png                PWA icon (512×512)
├── assets/                     The game: one minified JS bundle + one stylesheet
├── readable/                   De-minified, human-readable copy of the bundle (reference only)
├── screenshots/                In-game screenshots used by the README
├── docs/                       The Mayor's Handbook (this book)
└── .gitbook.yaml               GitBook configuration (root: ./docs)
```

## The entry point

### `index.html`

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="..." />
    <meta name="theme-color" content="#182624" />
    <meta name="description" content="Lundby — a living city, shaped by you. ..." />
    <link rel="manifest" href="./manifest.webmanifest" />
    <link rel="apple-touch-icon" href="./icon-192.png" />
    <title>Lundby · A city, shaped by you</title>
    <link rel="icon" type="image/png" href="./favicon.png" />
    <script type="module" crossorigin src="./assets/index-DSsDKc7J.js"></script>
    <link rel="stylesheet" crossorigin href="./assets/index-BbaH3kXg.css">
    <meta name="lundby-build" content="fbfcf42e0d95960f">
  </head>
  <body>
    <div id="root"></div>
  </body>
</html>
```

The entry point:

- Loads the JS bundle as an ES module.
- Loads the stylesheet.
- Injects the build hash as `<meta name="lundby-build">`.
- Mounts the React app into `#root`.

> *The whole game is one minified ES-module bundle
> (`assets/index-DSsDKc7J.js`, ~4.3 MB) with Three.js bundled in; the
> `readable/` copy is prettified for study and is not executed.*

## The bundle

### `assets/`

The shipped game.

- `assets/index-DSsDKc7J.js` — the minified bundle.
- `assets/index-BbaH3kXg.css` — the minified stylesheet.

The hash in the filename is content-hashed. Bump it whenever the
file changes.

> *This standalone file includes the game's scripts, styles, and
> fonts.*

## The readable copy

### `readable/`

- `readable/index.js` — a de-minified, human-readable copy of the
  bundle.

This file is **for reading and reference only**. The game loads
`assets/index-*.js`, not this file.

> *The `readable/` copy is prettified for study and is not
> executed.*

## The PWA shell

### `manifest.webmanifest`

The PWA manifest. Tells the browser how to install Lundby as a
standalone app.

### Icons

- `favicon.png` — the browser tab icon.
- `icon-192.png` — the 192×192 PWA icon.
- `icon-512.png` — the 512×512 PWA icon.

## Screenshots

### `screenshots/`

The screenshots used by the README. Each is a still of the running
game.

- `screenshots/startscreen.png` — the title screen.
- `screenshots/1.png`, `2.png`, `3-Streetview.png`, `4-Photo mode.png`,
  `5-Beyond your city.png`, `City-View.png` — the other stills.

> See the [README.md](../../README.md) for the screenshot
> descriptions.

## The handbook

### `docs/`

This book. Built with GitBook.

- `docs/README.md` — the landing page.
- `docs/SUMMARY.md` — the table of contents.
- `docs/part-1-welcome/` through `docs/part-7-save/` — the chapters.
- `docs/appendix-developers/` — the developer reference.
- `docs/assets/images/` — the image folder for the book.

> See [.gitbook.yaml](../../.gitbook.yaml) for the GitBook
> configuration.

## Tech notes

For a deeper look at the bundle and the service worker, see
[Tech notes](tech-notes.md).

For the string table that the handbook was extracted from, see
[The string table](the-string-table.md).

For how to contribute, see [Contributing](contributing.md).

---

### Screenshots to capture
- ![alt: The project layout in a file tree. A graphical representation of the directory structure described above. Folders are coloured, files are listed by name.](../../assets/images/appendix/project-layout.png "The project layout")
