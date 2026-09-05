# Roads

> *Two-lane neighborhood road. Carries power and water beneath it. Drag to draw.*

Roads are the spine of every city. They carry cars, trucks, buses, and
streetcars — and they carry power and water beneath them too. A connected
road network is what turns zoning into a city.

## The road types

Lundby has three families of road, each with a different capacity and
purpose.

### Local street
*Two-lane neighborhood road. Carries power and water beneath it. Drag to draw.*

- The basic road. Cheapest, quietest, and the default for residential
  neighborhoods.
- Carries cars, trucks, and bicycles. Power and water run beneath it
  automatically.

### Avenue
*Four lanes with more traffic capacity. Build across water to create a bridge.*

- Higher capacity, higher speed. Use for arterials, downtowns, and
  bus-and-streetcar corridors.
- Can host **streetcar tracks** and **bus routes** on the same right of way.

### Highway
*High-capacity regional road. Expensive to build and maintain.*

- Long-distance, high-speed connections.
- Connects to the **regional road** that runs to the edge of the map.

## Drawing tools

Open the **Roads** tool to see the road shapes.

| Tool | What it does |
| --- | --- |
| **Straight** | *Drag between two points. Hold Shift for 45° angles.* |
| **Right angle** | *Drag between two points for a right-angle road.* |
| **Arc** | *Drag between two endpoints for a constant-radius arc.* |
| **Circle** | *Drag at least 2 tiles from the center to make a circle.* |
| **Block** | *Drag opposite corners to leave space inside the block.* |
| **Square block** | *Drag opposite corners. Hold Shift for a square block.* |
| **Bend** | *Choose a bend and direction, then drag between two endpoints.* |
| **Sweeping bend** | A larger-radius version of the bend tool. |
| **Wide bend** | An even larger arc. Useful for highways. |
| **Gentle bend** | A subtle curve. Good for avenues. |

> *Leave clearance between the road and nearby buildings.*
> *Leave room for the curved road and its sidewalk.*

## Road design

### One-way streets
*Drag along at least two tiles to set the one-way direction.*

One-way streets double the effective capacity of a road in a single
direction. Useful for bus corridors, downtown grids, and any road that
needs predictable traffic flow.

> *Draw over existing streets to restore both directions.*
> *Reverse traffic direction* to flip a one-way.
> *Incoming traffic only · add a return connection* if you forgot the
> return trip.

### Setbacks and curves
A road's setback is the space it needs to either side, including
sidewalks. Curved roads need more setback than straight ones.

> *This lot is inside the curved road setback.*

### Bridges
*Four lanes with more traffic capacity. Build across water to create a bridge.*

Any road can cross water — just draw it across. The game will build a
bridge. *Build across water to create a bridge.*

> *This bridge cannot be removed yet.* Once a bridge is built, it has
> to be explicitly removed.

### Bulldozer
*Bulldozer · B*

The bulldozer clears anything in its path. Use it for:

- Removing a misplaced road.
- Clearing trees and rubble before building.
- Re-shaping a neighborhood.

> *Remove a building, road, zone, or tree. Drag to clear an area.*

## Road spacing guides

When you're drawing, faint dashed lines show where parallel roads will
fit. **Show dashed future road centers beside nearby straight roads** is
on by default.

> *Distance between road centerlines.* The spacing guide is a fixed
> distance, but you can adjust it for individual roads.

## Traffic

Once roads are in, traffic appears. Cars, trucks, buses, and streetcars
share the network. Each vehicle has a model and a route, and the
simulation tries to find a path for every journey.

- *Representative commuter street traffic* — a sample of journeys.
- *Detailed street actors* — every car, every truck, every streetcar.
- *Traffic congestion* — the data layer that shows where roads are
  over capacity.

## Maintenance

Roads have a **maintenance / month** cost based on their length and
type. Highways are the most expensive. The cost is in the **Road & rail
maintenance** line of the budget.

## Tips & common pitfalls

- **Connect to the edge of the map early.** The regional road connection
  unlocks trade and regional services.
- **Don't make one-way streets one-way in the wrong direction.** The
  arrow on the road shows the direction; the *Flip road arc* and *Flip
  road curve* buttons help with mistakes.
- **Curves cost more to maintain** than straights. Use them where they
  earn their keep — at intersections and at the entrances to
  neighborhoods.
- **Avenues with streetcar tracks** are the most cost-effective rapid
  transit you can build. See [Public transit](part-3-utilities/public-transit.md).

## Related pages

- [Zoning](zoning.md)
- [Bridges and terrain](bridges-and-terrain.md)
- [Public transit](part-3-utilities/public-transit.md)
- [The data layers](part-6-tools/the-data-layers.md)

---

### Screenshots to capture
- ![alt: The Roads tool open. Road types in a row: Local street, Avenue, Highway. Below: a grid of shape tools — Straight, Right angle, Arc, Circle, Block, Bend, Sweeping bend, Wide bend, Gentle bend. The Straight tool is selected.](../../assets/images/build/roads-tool.png "The roads tool — types and shapes")
- ![alt: An avenue under construction. Four lanes, a center reservation, a bike lane on each side. Bus stops and a streetcar track are visible. The road crosses a small river on a bridge.](../../assets/images/build/roads-avenue.png "An avenue with streetcar tracks and a bridge")
- ![alt: A one-way street in a downtown grid. The arrows painted on the road show the direction. A bus is travelling along it. The "Street directions or a track gap prevent a complete streetcar loop" warning is visible in the panel.](../../assets/images/build/roads-oneway.png "One-way streets in a downtown grid")
- ![alt: A road spacing guide visible while drawing a new road. Faint dashed lines show the future centerlines of two parallel roads on either side. A small overlay reads "Distance between road centerlines."](../../assets/images/build/roads-spacing.png "Road spacing guides")
- ![alt: The bulldozer tool active, clearing a damaged road. A red area shows the footprint being removed. A warning reads "Removing the main building clears the whole site."](../../assets/images/build/roads-bulldozer.png "Bulldozer clearing a damaged road")
- ![alt: The traffic congestion data layer active. Roads are coloured from green (free flow) to orange (slow) to red (jammed). The legend in the corner reads "Green streets flow freely. Orange streets need attention."](../../assets/images/build/roads-congestion.png "Traffic congestion data layer")
