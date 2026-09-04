# Lundby · A city, shaped by you

An original 3D city-building simulation. Zone neighborhoods, lay roads and rail, keep
the lights on and the books balanced, and grow a coastal village into a living region —
all in your browser, no install required beyond a tiny local web server.

Lundby is a fully static web app (a single minified JavaScript bundle built on
[Three.js](https://threejs.org)/WebGL). There is no build step, no backend, and no
dependency to install — any web server will do.

## Screenshots

> **TODO:** capture these from the game and save them into the `screenshots/` folder,
> replacing the placeholder filenames below.

<!-- 1. Screenshot: title / scenario selection screen -->
![Lundby title and scenario selection screen](screenshots/01-title-screen.png)
*The title screen: choose a blank map, take over Lundby Bay, or play one of three timed challenges.*

<!-- 2. Screenshot: mid-game city overview with roads, zones, and services visible -->
![A mid-game city viewed from above](screenshots/02-city-overview.png)
*A growing city: zoning, transit, power, and services at street level.*

<!-- 3. Screenshot: a management panel such as the budget, council, or tax screen -->
![The city management interface](screenshots/03-city-management.png)
*Running the city: treasury, taxes, council departments, and regional policy.*

## Features

**Building & zoning**
- Residential, commercial, and industrial zoning with demand-driven growth
- Farms, mines, parks, stadiums, hotels, a university, and a public library
- Free camera (pan / rotate / zoom) over a hand-built 3D world with day-night cycle,
  street lighting, and rainy-weather effects

**Utilities & infrastructure**
- Power grid: coal, solar, and wind generation
- Water towers and pumping stations
- Garbage and emergency services (fire, police, hospitals, schools)

**Transportation**
- Roads with live traffic simulation, buses, trams, and metro
- Passenger and cargo rail (Lundby Rail), freight yards, and a trade depot
- Ferries, marina and cargo terminal, and an international airport

**Economy & civics**
- Treasury, budget, and revenue tracking; bonds; taxes — including separate
  residential tax rates by household income
- City council with departments that unlock as the city grows; approval rating
- Milestone grants, tourism, and regional services shared across neighboring cities
  (Cedar Hollow, Eastbank, Silver Coast)

**Simulation depth**
- Population growth and decline, employment, land value, pollution, education, commuting
- Weather and disasters
- Sandbox mode, tutorial, difficulty settings, and simulation speed controls

**Maps & scenarios**
- Four terrain types: coastal bay, river valley, highlands, islands
- Five starts: *Your own horizon* (open ended), *Lundby Bay* (living city), and three
  timed challenges — growth, environment, and recovery

**Saves**
- Autosave, a recovery slot, and three manual save slots (kept in the browser's
  `localStorage`)
- Export/import cities as `.lundby` files for backup or transfer

## Requirements

- Any modern browser with WebGL 2 support (current Chrome, Edge, Firefox, or Safari)
- Python 3 **or** Node.js **or** Docker — whatever is easiest, just to serve the files

> The game must be served over HTTP; opening `index.html` directly from disk will not
> work, because browsers block ES-module scripts on the `file://` protocol.

## Install & run

Get the files (copy this folder or `git clone` it), then start a web server in the
project root. Any port works; the examples use `9090`. Open
`http://localhost:9090/` in your browser afterwards.

### Windows

```powershell
cd C:\path\to\lundby
py -m http.server 9090
# or: python -m http.server 9090
```

### macOS

```bash
cd /path/to/lundby
python3 -m http.server 9090
```

### Linux

```bash
cd /path/to/lundby
python3 -m http.server 9090
```

### Alternatives (any OS)

```bash
# Node.js
npx serve -l 9090 .

# Docker
docker run --rm -p 9090:80 -v "$PWD:/usr/share/nginx/html:ro" nginx
```

## Playing

1. Pick a scenario on the title screen — *Your own horizon* is the classic open-ended
   start on the terrain of your choice; *Lundby Bay* drops you into a living city, and
   the three challenges are timed runs with specific goals.
2. Zone land, build roads and utilities, and watch demand respond as the city grows.
3. Balance the budget with taxes, bonds, and grants; unlock council departments and
   extend services region-wide as neighboring cities connect.
4. The game autosaves continuously; use the save slots and the export button
   (`.lundby` file) for anything you want to keep.

Tip: if you played an earlier build, do a hard refresh (**Ctrl+F5** / **Cmd+Shift+R**)
after updating the files so the browser picks up the new bundle.

## Saves & browser data

Saves live in your browser's `localStorage` for the origin you serve the game from
(e.g. `http://localhost:9090`). This means:

- Saves are per-browser and per-port — serving on a different port starts a fresh city list.
- Clearing site data wipes your cities; use **Export** for backups first.

## Project layout

```
index.html               Entry point (loads the bundle + injects the save tooling)
manifest.webmanifest     PWA manifest (installable as an app)
assets/                  The game: one minified JS bundle + one stylesheet
readable/                De-minified, human-readable copy of the bundle (reference only —
                         the game loads the file in assets/)
screenshots/             Screenshot placeholders (see Screenshots above)
```

## Tech notes

- The whole game is one minified ES-module bundle (`assets/index-DSsDKc7J.js`, ~4.3 MB)
  with Three.js bundled in; the `readable/` copy is prettified for study and is not
  executed.
- The app registers a service worker for offline play, but the worker file (`sw.js`)
  is not included in this copy — keep the local server running while you play.
