# Power grid

> *Power that reaches people.*

The power grid is the network that keeps the lights on. It runs from
power plants, through power lines, into roads, and out to every
building. If the grid is healthy, your city hums. If it browns out,
your city stalls.

## Power generation

Lundby has eight families of power plants, each with its own fuel,
output, and personality.

### Coal
*COAL GENERATION*

- The workhorse of the early game. Cheap to build, polluting to run.
- Needs a coal supply from a mine or imports.
- *Place a generator beside a connected road or import power through
  Region & trade.*

### Gas
*GAS GENERATION*

- Cleaner than coal, more flexible.
- Needs natural gas from a pipeline or imports.

### Oil
*OIL GENERATION*

- High output, high emissions. Useful as a peaker.
- *Stockpile this fuel in the industry warehouse or allow imports.*

### Solar
*SOLAR ENERGY*

- *Clean renewable power. Output varies with weather.*
- *Reliable clean generation with overnight battery storage* — when
  paired with the right tower.
- *Horizon solar array* — a landmark-scale solar farm.

### Wind
- *Clean renewable power. Output varies with weather.*
- *Advanced wind rotor* — the high-tier version.
- *Place a wind turbine beside your connected road. Roads carry power
  automatically.*

### Wave
*WAVE ENERGY*

- *Wave power station* — a coastal-only generation type.
- *A regional clean-energy field with grid-scale battery storage.*

### Nuclear
*NUCLEAR ENERGY*

- High output, low emissions, expensive to build and run.
- *Reactor fuel* and *Reactor quarter* — the inputs and a landmark
  annex.

### Fusion
*Fusion engineering*

- *Fusion power station* — the endgame generation type. Available in
  sandbox or after research.

## The power network

Power flows in this order:

1. **Generation** at a power plant.
2. **Transmission** along high-voltage power lines.
3. **Distribution** along the local power lines under roads.
4. **Demand** at every building that needs electricity.

> *Green means connected to a working electricity supply.* When the
> electricity map is on, connected buildings glow green; disconnected
> ones glow orange.

### Power lines
*Extends the electricity network beyond roads.*

- Place a power line to carry electricity away from a road.
- Power lines connect to other power lines, to buildings, and to
  generators.

> *Some homes need power.* If a home doesn't have power, the
> electricity map will show it in orange.

## Power and water through roads

> *Two-lane neighborhood road. Carries power and water beneath it. Drag
> to draw.*

By default, a road carries power and water along its length. You only
need separate power lines and water pipes when you want utilities to
leave the road.

## Buying and selling power

- *Import electricity* — buy power from the region.
- *Export surplus* — sell power to the region.
- *Power generation must be planned before fuel is consumed* — you
  can't order fuel for a plant that doesn't exist yet.

## Fuel

Most plants need fuel. Fuel comes from:

- **Local extraction** — coal mines, oil fields, ore mines.
- **Imports** — brought in by truck through the regional connection.
- **The industry warehouse** — *Stockpile this fuel in the industry
  warehouse or allow imports.*

> *A generator is low on fuel* — the warning you'll see when a plant is
> running out.

## Power reports

The **CITY POWER** panel (under *Energy & fuel*) shows:

- **Generation** — current output by plant type.
- **Demand** — what the city is drawing.
- **Rolling blackouts** — when demand exceeds supply, the city
  browns out.

> *Rolling blackouts* is the warning that appears at the top of the
> screen when generation can't keep up.

## Tips & common pitfalls

- **Diversify.** A single coal plant is fine in the early game, but a
  diversified grid (solar + wind + a peaker) is more resilient.
- **Power plants are buildings.** They need roads, water for cooling,
  and a workforce. Plan accordingly.
- **Reserve a backup.** A storm or a flood can take a plant offline.
  Have a peaker ready.
- **Don't brown out.** A sustained blackout halts jobs, services, and
  growth.

## Related pages

- [Water](water.md) — many plants need water for cooling.
- [Weather and disasters](part-5-simulation/weather-and-disasters.md) —
  the disasters that can take a plant offline.
- [The data layers](part-6-tools/the-data-layers.md) — the electricity
  map.

---

### Screenshots to capture
- ![alt: The Power category in the build menu. Eight cards: Coal power station, Gas power plant, Oil power station, Solar farm, Wind turbine, Wave power station, Nuclear station, Fusion power station. The Coal card is selected, showing cost and a one-line description.](../../assets/images/utilities/power-tool.png "The power build menu — eight generation types")
- ![alt: A coal power station beside a road, with a stockyard of coal next to it. Smoke rises from the stacks. The electricity map is on, and the surrounding blocks glow green.](../../assets/images/utilities/power-coal.png "A coal power station online")
- ![alt: The electricity map active. Roads are coloured green where power is connected, orange where it's not. A small legend reads "Green means connected to a working electricity supply." A power line runs to an outlying industrial block.](../../assets/images/utilities/power-map.png "The electricity map")
- ![alt: A coastal wind farm. Five wind turbines on a ridge, with a wave power station in the water below. The horizon glow shows the time of day (early evening). A "Power generation: 12.4 MW" indicator is in the corner.](../../assets/images/utilities/power-renewables.png "A wind and wave farm")
- ![alt: A rolling blackout warning. The top of the screen reads "Rolling blackouts" in red. Buildings in the affected block are dark. The CITY POWER panel shows demand exceeding supply.](../../assets/images/utilities/power-brownout.png "A rolling blackout")
