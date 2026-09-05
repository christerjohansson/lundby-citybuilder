# Offline play and updates

> *Offline play and updates*

Lundby can be played offline. The game caches the bundle, the assets,
and the offline data so you can keep playing when the network is
down. The same system also handles game updates.

## Where to find it

- **City → Settings → Offline**

> *Offline play and updates* — the section.
> *Offline files need attention* — the warning.
> *Offline play and updates* — the section header.
> *Offline* / *OFFLINE* — the status.
> *Offline preparation* — the prep step.

## How offline play works

When you load the game for the first time, the service worker
caches:

- The game bundle.
- The stylesheet.
- The fonts.
- The offline data.

After that, the game runs without a network connection. Saving still
works (your saves are in `localStorage`), and the simulation still
runs.

> *Checking this build's offline files…* — the cache check.
> *Finishing offline preparation for this build…* — the prep step.
> *Preparing offline play* — the prep step.
> *Ready offline* — the all-clear.
> *Some offline files are missing. Keep the server available and
> check again.* — the warning.
> *The offline build response is invalid.* — the error.
> *The active offline worker did not confirm this build.* — the
> error.
> *The offline update could not finish. Keep the server available
> and check again.* — the error.
> *Offline preparation could not finish.* — the error.
> *The offline build response is invalid.* — the error.
> *Activating update…* — the update flow.
> *Game update ready* — the all-clear.
> *Save & reload update* / *Reload update; keep original* — the
> actions.
> *The game could not activate the update. Your saved city is
> unchanged.* — the failure.
> *The simulation update is too large.* — the error.
> *The simulation update could not be read.* — the error.
> *The city changed while a simulation update was being prepared.*
> — the conflict.
> *The day could not advance.* — the simulation error.
> *The autosave could not be decompressed.* — the save error.

## Playing offline

1. Load the game once with a network connection.
2. Wait for the offline files to cache.
3. Disconnect from the network.
4. The game continues to run.

> *If you played an earlier build, do a hard refresh (Ctrl+F5 /
> Cmd+Shift+R) so the browser picks up the new bundle and clears any
> stale service worker.*

## Game updates

When a new build is available:

1. The game shows *Game update ready* in the management menu.
2. Click **Save & reload update**.
3. The new bundle is downloaded and activated.
4. Your saved city is preserved.

> *Reload update; keep original* — the alternative.
> *The game could not activate the update. Your saved city is
> unchanged.* — the failure.

## Why the service worker matters

> *This standalone file includes the game's scripts, styles, and
> fonts.* — the cache description.
> *WARNING: Multiple instances of Three.js being imported.* — the
> development warning.

The service worker is the small piece of code that caches the game
files. It's registered automatically when you load the game.

> *Check offline files & updates* — the menu link.

## Saving and loading offline

> *Saves are per-browser and per-port — serving on a different
> port starts a fresh city list.*

Saves work offline because they're in `localStorage`. Export to
`.lundby` for a backup that survives any browser reset.

> *Clearing site data wipes your cities; use **Export** for backups
> first.*

## The local web server

> *The game must be served over HTTP; opening `index.html` directly
> from disk will not work, because browsers block ES-module scripts
> on the `file://` protocol.*

Even for offline play, the game needs a local web server. The server
runs in the background and serves the cached files to the browser.

> *Check again* — the action.

## Tips & common pitfalls

- **Hard refresh after an update.** A normal reload may use the
  cached old bundle.
- **Keep the local server running.** The service worker uses it to
  cache the files.
- **Different ports = different saves.** *Serving on a different
> port starts a fresh city list.*
- **Browser reset wipes saves.** Always export before clearing site
> data.

## Related pages

- [Save and load](save-and-load.md) — the save workflow.
- [Getting started](part-1-welcome/getting-started.md) — the
  install steps.
- [Tech notes](appendix-developers/tech-notes.md) — how the service
  worker is built.

---

### Screenshots to capture
- ![alt: The offline play and updates panel. A status: "Ready offline" with a green check. A "Game update ready" notice is visible. A "Save & reload update" button is at the bottom.](../../assets/images/save/offline-ready.png "Ready offline, with a pending update")
- ![alt: A loading screen during an offline file check. The text reads "Checking this build's offline files…" A progress bar is at 60 %.](../../assets/images/save/offline-check.png "Offline file check in progress")
- ![alt: A browser showing the game running with the network disconnected. The title bar shows the localhost URL. The game is running normally — the city is on the screen, the simulation is running.](../../assets/images/save/offline-running.png "The game running offline")
