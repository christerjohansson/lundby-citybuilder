# Zoning

> *Choose what grows here.*

Zoning is how you tell the city what a piece of land is *for*. Once a zone
is connected to a road, power, and water, the city fills it in with
buildings that match the zone.

## The five zone types

Lundby has five zone types, each with its own role in the simulation.

### Residential
*Homes for your citizens. Needs roads, jobs, and clean utilities.*

- Houses, apartments, and tower residences grow here.
- Demand rises with employment, education, low pollution, and good
  services.
- **Income groups:** *Lower income*, *Middle income*, and *Affluent*
  households all share the residential zone. The colour of the household
  pin tells you which group lives there:
  - **Slate** — lower income
  - **Green** — middle income
  - **Gold** — affluent

### Commercial
*Shops and restaurants. Thrives near residents and visitors.*

- Local shops, markets, and shopping galleries.
- Demand rises with nearby residents, retail wealth, and visitor arrivals.
- Commerce reports break down by shopper: residents, visitors, and
  commuters.

### Industrial
*Manufacturing jobs and export goods. Keep pollution away from homes.*

- Farms, mines, factories, and processing plants.
- Generates jobs, freight, and pollution. Pair with parks and clean
  industry standards to keep homes happy.
- **Industry sections:** light industry, basic manufacturing, advanced
  manufacturing, and corporate industry. Each has different output and
  pollution profiles.

### Office
*Clean, high-value jobs for an educated workforce.*

- Office towers, civic blocks, and creative studios.
- Demand rises with educated residents and a connected transit network.
- Offices are the natural neighbour for residential at the top of the
  income ladder.

### Agricultural
*Local food and rural employment with low utility demand.*

- Farms and orchards. Low impact, low revenue, but they keep the rural
  landscape working.
- Can be placed on undeveloped land without roads, but they need road
  access to ship output.

## How to zone

1. Open the **Zoning** tool from the build menu.
2. Pick the zone type.
3. Pick a **brush size**.
4. Click or drag to paint the zone onto the map.
5. The zone appears as a coloured overlay. The demand panel tells you
   whether the city wants more.

> *Click or drag to build.*

## Density

Each zone can be painted at three densities:

- **Low** — small buildings, low impact.
- **Medium** — typical city blocks.
- **High** — tall buildings, high demand, high impact.

Density is set by the brush, and you can mix densities in the same
neighbourhood. The city will pick the highest density that fits the
demand.

## Demand

The **demand panel** shows three bars: residential, commercial, and
industrial. When a bar is green, the city wants more of that zone; when
it's red, you have too much.

- **Residential** rises with employment, happiness, and clean services.
- **Commercial** rises with nearby residents, retail wealth, and visitor
  arrivals.
- **Industrial** rises with manufacturing demand, exports, and raw
  material access.

A new growth demand is one of the most important signals in the game.
**GROWTH DEMAND** appears at the top of the screen when a zone is ready
to expand aggressively.

## Growth

Once a zone is connected to roads, power, and water:

1. The city picks a building that matches the zone, density, and
   neighbourhood.
2. Construction begins. *Under construction* buildings have scaffolding.
3. Once built, the building starts operating — households move in,
   businesses open, factories begin production.

> *Abandoned — repair or redevelop.* If a building is damaged and not
> repaired, it may be abandoned. Restore it with a repair crew, or demolish
> it and let something new grow.

## Building tiers

Most building types have multiple tiers. The tier a building reaches
depends on the surrounding wealth, services, and education. *Highest tier ·
maintain the workforce and customers.*

> *Building size and business tier develop separately.* A small building
> can be a high-tier business; a large building can be a low-tier one.

## Tips & common pitfalls

- **Don't over-zone.** A sea of residential with no commercial means no
  shops, and shops are what keep residents happy.
- **Industrial pollution drives residents away.** Keep a buffer — a park,
  a road, a coast — between heavy industry and homes.
- **Density compounds.** A high-density residential block next to a
  high-density commercial block is a transit demand waiting to happen.
- **Zoning is cheap; demolishing is not.** A bulldozer is faster than
  fixing a bad layout.

## Related pages

- [Roads](roads.md) — the spine of every zone.
- [Districts and policies](districts-and-policies.md) — paint a district
  to give it a local policy.
- [Commerce and shoppers](part-5-simulation/commerce-and-shoppers.md) —
  what the commercial zones are doing.
- [Population and households](part-5-simulation/population-and-households.md) —
  what the residential zones are doing.

---

### Screenshots to capture
- ![alt: The Zoning tool open. Five zone types are visible as cards: Residential (green), Commercial (blue), Industrial (orange), Office (purple), Agricultural (yellow). The brush size selector is at the bottom.](../../assets/images/build/zoning-tool.png "The zoning tool with all five zone types")
- ![alt: A small neighborhood viewed from above. Three residential blocks (green), one commercial strip (blue), one office block (purple). Demand panel on the right: residential green, commercial green, industrial red.](../../assets/images/build/zoning-mixed.png "A mixed neighborhood with healthy demand")
- ![alt: A close-up of the residential brush painting a new block. The brush is showing a 3x3 footprint, and the zone appears as a translucent green overlay as the player drags. The build menu shows the cost and the current paint area.](../../assets/images/build/zoning-brush.png "Painting residential zoning")
- ![alt: A new residential building under construction. Scaffolding covers the facade, a small crane is at the top, and a green progress bar reads "Construction in progress — 4 days remaining."](../../assets/images/build/zoning-construction.png "A new building under construction")
- ![alt: An abandoned residential building. The roof is partially collapsed, windows are dark, and a warning icon floats above. The building's tooltip reads "Abandoned · restore this building."](../../assets/images/build/zoning-abandoned.png "An abandoned building")
