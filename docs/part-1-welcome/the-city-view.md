# The city view

> *Interactive 3D city map. Drag to pan, right-drag to rotate, scroll to zoom.*

The city view is a free 3D camera over a hand-built world. Day turns to
night, the lights come on, the rain falls, and your city lives.

## The two cameras

Lundby has two cameras. Switch between them with the camera buttons at the
top of the screen.

- **Perspective** — *Perspective · depth and a natural skyline.* The
  default. Drag to pan, right-drag to orbit, scroll to zoom.
- **Planning** — *Planning · parallel streets and precise layout.* A
  top-down orthographic view. Useful for laying out roads and zoning on a
  grid.

## Camera controls

| Action | Mouse | Keyboard |
| --- | --- | --- |
| **Pan** | Left-drag | **W / A / S / D** or arrow keys |
| **Orbit** | Right-drag | **Q / E** |
| **Zoom** | Mouse wheel / pinch | — |
| **Reset view** | Reset camera button | — |
| **Home view** | Home view button | **H** |
| **Raise camera angle** | Raise button | — |
| **Lower camera angle** | Lower button | — |
| **Rotate** | Rotate buttons | — |

> *Click a building to inspect. Drag to pan; right-drag to orbit.*

## What you see

- **Streets and traffic.** Cars, trucks, and streetcars move along the
  road network. *Representative commuter street traffic* shows a sample
  of journeys; *Detailed street actors* shows them in full.
- **Day and night.** A day-night cycle runs by default. *The light changes
  as your city grows* — the cycle is tuned to the population.
- **Street lighting.** Street lights come on at night. Their field
  dimensions match the city layout.
- **Weather.** Rain falls, fog rolls in, clouds drift overhead. See
  [Weather and disasters](part-5-simulation/weather-and-disasters.md).
- **People and life.** Walking, shopping, and resting neighbours fill
  the streets. The detail level depends on your graphics setting.
- **Birds and boats.** Coastal birds glide and flap. Coastal freighters
  push wakes across the water.

## Time of day

The day-night cycle is automatic, but you can also **change time of day**
manually from the management menu. Useful for screenshots.

## Photo mode

Press the camera button to enter **photo mode**. From there you can:

- Frame the shot.
- Change the time of day.
- Record 10 seconds of video.
- Save the photograph as a PNG.

See [Photo mode](part-7-save/photo-mode.md) for the full walkthrough.

## Tips & common pitfalls

- Right-drag is your friend. The perspective camera's orbit feels strange
  until you get used to it.
- The minimap in the corner is a **click-to-move** view. Click anywhere on
  the minimap to send the camera there.
- The simulation runs in the background, but **rendering is the most
  expensive thing**. If your frame rate drops, drop the visual quality in
  *Settings*.
- Street actors are a graphics setting. If you don't need to see every
  pedestrian, turn them off.

## Related pages

- [The minimap](part-6-tools/the-minimap.md)
- [Photo mode](part-7-save/photo-mode.md)
- [Settings and graphics](part-6-tools/settings-and-graphics.md)
- [Keyboard and mouse](part-6-tools/keyboard-and-mouse.md)

---

### Screenshots to capture
- ![alt: The perspective camera high over a coastal city at noon. Residential, commercial, and industrial zones are visible, with the regional road in the distance. A HUD on the right shows the demand panel, the minimap is in the bottom-right, and the time of day indicator reads 12:00.](../../assets/images/welcome/city-view-perspective-noon.png "Perspective view at noon")
- ![alt: The same city from the planning camera — top-down, parallel streets, a clear grid of zoning. The road tool is open and a new avenue is being drawn in green.](../../assets/images/welcome/city-view-planning.png "Planning camera — top-down view")
- ![alt: The city at night. Street lights are on, the windows glow, and the day-night indicator reads 21:30. A faint rain is falling. The minimap shows the same city lit up at the edges.](../../assets/images/welcome/city-view-night.png "City view at night, light rain")
- ![alt: Photo mode active. The frame is a 16:9 rectangle, the time of day is set to 18:45 (golden hour), and a "Capture" button is in the bottom-right. The HUD is hidden.](../../assets/images/welcome/city-view-photo-mode.png "Photo mode — golden hour")
