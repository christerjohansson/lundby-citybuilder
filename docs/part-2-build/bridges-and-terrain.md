# Bridges and terrain

> *Lower cleared land. Below sea level, it becomes water.*

Lundby is a 3D world. Hills, valleys, and water shape every city. The
terrain tools let you raise, lower, and reshape land, and the road tools
will happily build bridges across water.

## The terrain tools

The terrain palette is its own tool, separate from the build menu.

### Raise terrain
*Raise cleared land or reclaim shallow water.*

- Click and drag to raise the height of cleared land.
- Reclaims shallow water into dry land.
- Cost depends on the area and the height change.

### Lower terrain
*Lower cleared land. Below sea level, it becomes water.*

- Click and drag to lower the height of cleared land.
- If you lower below sea level, the lowered area becomes water.
- Cost depends on the area and the height change.

> *Prepare an even site for construction.*
> *The terrain is already at this height limit.* You can't push terrain
> beyond its built-in min or max.

### Level terrain
- Levels an area to a chosen height.
- Useful for airport runways, transit terminals, and any large building
  that needs a flat site.

### Remediate ground
*Remediate cleared land · $100–$500 /tile*

- Cleans contaminated land so it can be developed.
- Required for some industrial sites and disaster zones.
- *Clear the land before remediating its soil.*

### Raise a protective bank
- Builds a small ridge along a coastline. Useful for flood defence.
- Banks can be raised and removed like any other terrain feature.

## Bridges

Any road drawn across water becomes a bridge automatically. The game
picks the bridge type based on the road type.

- *Build across water to create a bridge.*
- *This bridge cannot be removed yet.* — once built, a bridge has to be
  removed with the **Remove bridge** tool.
- *Remove this bridge for $X* shows the cost.

### Bridge tips
- **Avenue bridges** look the best and have the most capacity.
- **Local street bridges** are cheap and quick to build.
- **Highway bridges** are expensive but necessary for long crossings.
- A bridge's clearance is fixed. Make sure boats and ferries can pass
  underneath if you need them to.

## Slope and grade

Roads have a maximum grade. If the terrain is too steep, the road tool
will warn you: *A guideway gap, steep grade or submerged deck interrupts
this line.*

For steep terrain:

- Use the terrain tools to terrace the slope.
- Use switchbacks (a series of curves up a hill).
- Use elevated guideways for transit (see [Public transit](part-3-utilities/public-transit.md)).

## Floodwater

Coastal bays and river valleys have water that can rise. When it does,
low-lying sites flood.

- *Sites directly closed by water* — sites that are currently under
  floodwater.
- *Flooded · generation suspended* — a power plant that's out of action.
- *Airport inundated by floodwater* — same idea for an airport.
- *The plant is inundated; wait for floodwater to recede.*

> See [Weather and disasters](part-5-simulation/weather-and-disasters.md)
> for the full disaster list.

## Tips & common pitfalls

- **Terrain changes are expensive.** Plan the big moves before you start
  raising a hill.
- **Bridges are roads that happen to cross water.** They follow the same
  rules — one-way streets, avenues, streetcars all work on bridges.
- **Slope costs speed.** A steep grade slows traffic and breaks transit
  lines. Use the terrain tools or switchbacks to soften the climb.
- **Reclaimed land is fragile.** A reclaimed coast can flood if the
  disaster system triggers a surge.

## Related pages

- [Roads](roads.md)
- [Public transit](part-3-utilities/public-transit.md)
- [Weather and disasters](part-5-simulation/weather-and-disasters.md)

---

### Screenshots to capture
- ![alt: The terrain tool active. Four buttons in a row: Raise, Lower, Level, Remediate. The brush size is set to medium. A 3x3 area is being raised, the new height shown in a tooltip.](../../assets/images/build/terrain-tool.png "The terrain tool palette")
- ![alt: An avenue crossing a wide river on a multi-span bridge. The bridge has four lanes and a center reservation. Boat traffic is visible underneath. The minimap shows the river and the bridge in profile.](../../assets/images/build/terrain-bridge.png "An avenue bridge across a river")
- ![alt: A coastal city during a flood. The shore is underwater, low-lying residential blocks are partly submerged, and a "Floodwater warning" banner is at the top of the screen. A response car is heading to an incident.](../../assets/images/build/terrain-flood.png "Floodwater in a coastal city")
- ![alt: A highland city with switchback roads climbing a steep slope. The terrain tool has been used to terrace a small platform on the ridge. A new road is being drawn from the platform back down to the valley.](../../assets/images/build/terrain-switchback.png "Switchback roads in highlands")
