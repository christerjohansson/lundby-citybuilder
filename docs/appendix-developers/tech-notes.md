# Tech notes

> *A complete game in one file*

This page is for developers who want to understand the technical
shape of Lundby. It's a quick tour; the bundle is the source of
truth.

## The shape of the build

Lundby is a fully static web app:

- A single minified JavaScript bundle.
- A single minified CSS file.
- An `index.html` that loads them.
- A `manifest.webmanifest` and three icons.
- A service worker registered by the bundle (not present in this
  repository copy).

> *Lundby is a fully static web app (a single minified JavaScript
> bundle built on [Three.js](https://threejs.org)/WebGL).*

## The bundle

The shipped bundle is `assets/index-DSsDKc7J.js` — about **4.3 MB**
minified, ES module format, with **Three.js** bundled in. The
content-hash in the filename changes whenever the bundle changes.

> *The whole game is one minified ES-module bundle
> (`assets/index-DSsDKc7J.js`, ~4.3 MB) with Three.js bundled in; the
> `readable/` copy is prettified for study and is not executed.*

The minified bundle is a single line of JavaScript. It uses the
browser's ES module loader.

## React

The UI is built with **React**. The bundle includes React and React's
JSX runtime.

> *Minified React error #* — the React error number.
> *The argument must be a React element, but you passed* — a
> development error.
> *Objects are not valid as a React child (found:* — another
> development error.

## Three.js

The 3D view is built with **Three.js**, bundled into the main
bundle. The bundle includes:

- `THREE.WebGLRenderer`
- `THREE.PerspectiveCamera`
- `THREE.OrthographicCamera`
- `THREE.Scene`, `THREE.Mesh`, `THREE.InstancedMesh`
- `THREE.BoxGeometry`, `THREE.SphereGeometry`, `THREE.CylinderGeometry`,
  …the full geometry set.
- `THREE.ShaderMaterial`, `THREE.MeshStandardMaterial`, …the
  materials.
- `THREE.PMREMGenerator`, `THREE.CubeCamera`, …the IBL helpers.
- `THREE.OrbitControls` (for the camera).

> *WARNING: Multiple instances of Three.js being imported.* — the
> warning you'll see if a script imports Three twice.

## WebGL 2

The renderer requires **WebGL 2**. Browsers without WebGL 2 will
fail to start the 3D view.

> *The 3D view could not start* / *Your browser could not start the
> 3D renderer.* / *Error creating WebGL context.* / *Error creating
> WebGL context with your selected attributes.* — the failures.
> *Try a browser with WebGL 2 enabled.* — the suggestion.
> *WebGL 1 is not supported since r163.* — the Three.js warning.

## The simulation worker

The simulation runs in a **Web Worker**. The worker is created from
a blob URL inside the bundle.

> *Main-thread simulation* / *Main-thread transfer* — the messages
> that go between the main thread and the worker.
> *Background simulation* / *Invalid background simulation result.* —
> the worker errors.
> *Worker simulation* — the worker label.
> *The background simulation failed.* / *The simulation worker
> could not run.* / *The simulation worker could not receive the
> city.* / *The simulation worker did not respond.* / *The
> simulation worker has no city.* — the worker failures.
> *Worker change capture* — the capture mode.

## The service worker

The app registers a service worker for **offline play**. The
service worker file (`sw.js`) is **not included** in this
repository copy.

> *The app registers a service worker for offline play, but the
> worker file (`sw.js`) is not included in this copy — keep the
> local server running while you play.*

For local development, keep the local server running. The service
worker is registered automatically by the bundle.

## PWA

Lundby is installable as a Progressive Web App.

- `manifest.webmanifest` declares the app.
- `icon-192.png` and `icon-512.png` are the app icons.
- The browser shows an "Install" prompt when the app meets the
  installability criteria.

## The build hash

`index.html` declares a build hash in a `<meta>` tag:

```html
<meta name="lundby-build" content="fbfcf42e0d95960f">
```

This hash is used by the offline system to detect when a new
version of the bundle is available.

> *Game build* — the meta label.
> *Offline files need attention* — the warning.
> *Game update ready* — the prompt.
> *Activating update…* — the flow.

## The string table

The bundle contains a single minified line of JavaScript, but the
human-readable copy (`readable/index.js`) reveals a large string
table with the in-game text. The handbook was extracted from this
string table.

> See [The string table](the-string-table.md).

## Local development

To run the game locally:

1. Start a local web server in the project root.
2. Open the served URL in a browser.

Any port works. The examples use `9090`.

> *The game must be served over HTTP; opening `index.html` directly
> from disk will not work, because browsers block ES-module scripts
> on the `file://` protocol.*

## If you played an earlier build

> *If you played an earlier build, do a hard refresh (**Ctrl+F5** /
> **Cmd+Shift+R**) so the browser picks up the new bundle and clears
> any stale service worker.*

## Related pages

- [Project layout](project-layout.md) — the file tree.
- [The string table](the-string-table.md) — the in-game text.
- [Contributing](contributing.md) — how to contribute.

---

### Screenshots to capture
- ![alt: A diagram of the bundle's runtime: a browser loads index.html, which loads the JS bundle. The bundle contains React, Three.js, the game logic, and a service worker. The service worker caches the bundle. A Web Worker runs the simulation.](../../assets/images/appendix/tech-diagram.png "The runtime architecture")
- ![alt: The browser dev tools network tab showing the bundle being loaded. The bundle is 4.3 MB, the CSS is 200 KB. Both are served from the local web server.](../../assets/images/appendix/tech-network.png "The bundle in the network tab")
