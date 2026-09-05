# Getting started

> *A good city starts with you.*

Lundby runs in your browser. There is nothing to install beyond a tiny local
web server. Once it's serving, you pick a scenario, drop a few roads, zone
some land, and watch the city come to life.

## Before you play

You'll need:

- A modern browser with **WebGL 2** support (current Chrome, Edge, Firefox, or Safari).
- A local web server. Any of these will do:
  - `py -m http.server 9090` (Python 3)
  - `python3 -m http.server 9090` (macOS / Linux)
  - `npx serve -l 9090 .` (Node.js)
  - `docker run --rm -p 9090:80 -v "$PWD:/usr/share/nginx/html:ro" nginx`

> The game must be served over **HTTP** — opening `index.html` directly from
> disk won't work, because browsers block ES-module scripts on the
> `file://` protocol.

Open `http://localhost:9090/` after starting the server.

## Your first five minutes

1. **Pick a scenario** on the title screen. *Your own horizon* is the
   classic open-ended start; *Lundby Bay* drops you into a living city.
2. **Pick a terrain and a difficulty.** The terrain shapes your map; the
   difficulty changes your budget pressure.
3. **Build your first road.** Draw a short street from the edge of the map
   inward.
4. **Zone some land** along that road. Mix residential with a touch of
   commercial.
5. **Pause and look around.** Use the free camera to see your city from
   above, then from street level.

That's it. The city will start growing on its own once roads, power, and
water are connected.

## If you played an earlier build

Do a hard refresh (**Ctrl+F5** / **Cmd+Shift+R**) so the browser picks up
the new bundle and clears any stale service worker.

## Where to go next

- [The title screen](the-title-screen.md) — every option explained.
- [Choosing a start](choosing-a-start.md) — the five scenarios in detail.
- [The terrain types](the-terrain-types.md) — what each map gives you.
- [Tutorial walkthrough](tutorial-walkthrough.md) — a step-by-step first city.

---

### Screenshots to capture
- ![alt: Browser address bar pointed at http://localhost:9090/ with the title "Lundby · A city, shaped by you" in the tab. The 3D title screen is loading, the backdrop shows a hazy coastline.](../../assets/images/welcome/get-started-localhost.png "Local server up, title screen loading")
- ![alt: A small, hand-drawn 2-block neighborhood: one two-lane road with a short stub, residential zoning on both sides, no buildings yet. A power pole and a water tower are placed at the road's end.](../../assets/images/welcome/get-started-first-five.png "Your first five minutes — a single road, a power pole, a water tower, and zoning")
