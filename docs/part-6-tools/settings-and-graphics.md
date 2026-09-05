# Settings and graphics

> *Settings* / *Visual quality*

The settings panel is where you tune the game's appearance, sound,
and simulation speed. It's also where you can save the city, export
a `.lundby` file, and adjust the difficulty and sandbox.

## Where to find it

- **City → Settings**
- Or click the settings button in the toolbar.

> *Settings* / *Settings2* — the link.
> *Settings* — the section.

## Graphics

> *Visual quality* / *Graphics* / *Graphics quality* — the section.

The graphics settings control how the 3D world looks.

### Visual quality

The three presets:

- **High** — *High · full detail & shadows* — the full experience.
- **Balanced** — *Balanced · lighter rendering* — the default.
- **Performance** — *Performance · no shadows* — for low-end
> hardware.

> *Adaptive resolution* — the auto-adjust toggle.

### Camera projection

> *Camera projection* — the toggle.
> *Perspective camera* / *Orbit camera* / *Perspective view* /
> *Planning view* / *Natural view* / *Planning · parallel streets and
> precise layout* — the camera modes.
> *Switch to the perspective camera* / *Switch to the planning
> camera* — the actions.

### Other graphics

> *Atmospheric recovery* / *Sparkles* / *Sparkles* — the visual
> effects.
> *Animated flame wisps* / *Layered smoke and cooling steam* /
> *Rising embers* / *Animated flame wisps* — the fire effects.
> *Navigation lights* / *Sparkles* / *Rising embers* — the lights.
> *Coastal mist* / *Coastal birds — gliding and flapping* / *Sailing
> marina* — the coastal effects.
> *Operating plaza fountain spray* / *Lundby illuminated pavement* —
> the urban details.

## Sound and atmosphere

> *Sound & atmosphere* / *Ambient soundtrack* / *City sounds* /
> *Atmospheric recovery* — the sound section.

- *An original, generative piano-like soundscape.* — the music
> description.
- *Ambient soundtrack* — the music toggle.
- *City sounds* — the ambient toggle.
- *Gentle feedback for building and city actions.* — the UI sounds.

## Simulation speed

> *Simulation speed* / *Simulation speed* — the slider.
> *Pause simulation* / *Resume simulation* / *SIMULATION PAUSED* —
> the pause actions.
> *Advance one day* / *Advance one day while paused* / *Advance one
> day while paused · .* — the advance actions.
> *Pause / resume* — the toggle.
> *Simulation paused after an unexpected update error.* — the
> warning.

The simulation speed slider controls how fast the simulation runs
relative to real time. Faster speeds mean more days per minute, but
the game is less responsive.

## Time of day

> *Time of day* / *Change time of day* — the control.
> *The light changes as your city grows.* — the flavour.

The time of day control lets you set the time manually, overriding
the day-night cycle. Useful for screenshots.

## The 3D view

> *The 3D view could not start* / *Your browser could not start the
> 3D renderer.* — the failure messages.
> *Error creating WebGL context with your selected attributes.* /
> *Error creating WebGL context.* / *The city view needs a restart.*
> — the error variants.
> *Try a browser with WebGL 2 enabled.* — the suggestion.
> *Live performance counter* / *Live frame rate* / *Current frame
> rate* / *Show the frame rate while the simulation runs.* — the
> performance overlay.

## The simulation worker

> *Main-thread simulation* / *Main-thread transfer* — the main-thread
> messages.
> *Background simulation* / *Invalid background simulation result.*
> — the worker messages.
> *Worker simulation* — the worker label.
> *The background simulation failed.* / *The simulation worker
> could not run.* / *The simulation worker could not receive the
> city.* / *The simulation worker did not respond.* / *The simulation
> worker has no city.* — the worker errors.
> *Worker change capture* — the capture mode.

## Difficulty and sandbox

See [Difficulty and sandbox](part-1-welcome/difficulty-and-sandbox.md).

## Save and load

See [Save and load](part-7-save/save-and-load.md).

## Tips & common pitfalls

- **Visual quality is the biggest perf lever.** Drop to *Balanced*
  if your frame rate suffers.
- **Sound is a setting.** If you're playing in a quiet room, you
  can mute the ambient soundtrack.
- **Simulation speed is the second-biggest perf lever.** Pause the
  simulation if you're not actively playing.
- **Time of day is for screenshots.** Set it manually and the day
  stops moving.

## Related pages

- [Difficulty and sandbox](part-1-welcome/difficulty-and-sandbox.md)
  — the difficulty settings.
- [Save and load](part-7-save/save-and-load.md) — the save settings.
- [The city view](part-1-welcome/the-city-view.md) — the cameras.

---

### Screenshots to capture
- ![alt: The settings panel. A vertical list of sections: Graphics, Sound & atmosphere, Simulation speed, Time of day, Difficulty, Sandbox, Save & load, About. The Graphics section is open, showing the visual quality slider and the camera projection toggle.](../../assets/images/tools/settings-graphics.png "The graphics settings")
- ![alt: The simulation speed control. A slider with five positions: Pause, Slow, Normal, Fast, Fastest. The slider is on Normal. A "Live frame rate" indicator reads "60 fps" in the corner.](../../assets/images/tools/settings-simulation.png "The simulation speed control")
- ![alt: The graphics settings with the quality slider at "Balanced · lighter rendering." A preview shows the city in balanced mode. An "Adaptive resolution" toggle is on.](../../assets/images/tools/settings-quality.png "The visual quality preset")
