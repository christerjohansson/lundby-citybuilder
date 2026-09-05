# Buildings and towers

> *A city with a life of its own.*

Lundby's buildings range from small shops to eight-level towers with sky
bridges. Most are placed from the build menu, but a few — landmarks,
great works, and the tallest towers — have their own editor.

## Placeable buildings

The build menu is the easiest way to find what to place. It's organised by
category:

- **Power & industry** — coal, gas, oil, solar, wind, wave, nuclear,
  fusion, and the resource economy.
- **Water & agriculture** — water towers, pumping stations, treatment
  plants, farms, orchards.
- **Waste & recycling** — collection, landfill, recycling, ground
  recovery.
- **Public safety** — fire stations, police stations, clinics, hospitals.
- **Schools & learning** — primary, secondary, university, library.
- **Transit & freight** — bus depots, streetcar depots, metro stations,
  maglev stations, rail depots, ferry terminals, airports.
- **Commercial** — corner shops, markets, retail galleries, hotels,
  attractions.
- **Parks & leisure** — neighborhood parks, stadiums, plazas.
- **Great works** — landmark projects with their own progression.

Each card shows a small preview, the cost, and a one-line flavor
description. Hover for more.

## Standard placement

For most buildings, the steps are:

1. Open the build menu and pick the category.
2. Click the building you want.
3. Move the cursor over the map. A ghost of the building follows the
   cursor.
4. Press **R** to rotate.
5. Click to place.

> *Rotate · R*
> *Click or drag to build*
> *Needs working roads, power and water* — many buildings need all three.

## The tower editor

Towers are big buildings with multiple levels — podium, mid levels, and a
roof crown. The tower editor is the place where you add, remove, and
rearrange them.

> *Use the tower editor to add or replace levels.*

### How to enter
1. Place the tower's **podium** from the build menu.
2. Click the podium to inspect it.
3. Click **Open tower editor** in the inspector.

### What's in a tower

A tower has three parts, from the ground up:

1. **Podium** — the base. Most towers need a podium before you can add
   levels. *Finish the tower podium first.*
2. **Levels** — the floors in between. Up to **eight levels** per tower.
   *Complete all eight levels before building a crown.*
3. **Crown** — the roof. Pick from a catalog of roof crowns.
   *Choose a roof crown.*

### Adding a level
- In the editor, pick a level from the **tower level catalog**.
- Pay the cost.
- The level is added on top of the podium.
- *Finish the current level before starting another.*

### Replacing the crown
- *Remove the existing crown before replacing it.*

### Removing levels
- *Remove this level permanently?* — the prompt for a paid level.
- *Remove tower levels from the top down, starting with the crown.*

### Clearing a whole tower
- *Clear this entire tower, including every paid level and its crown?*
- *Confirm whole tower demolition*

### Skybridges
- *Add a Skybridge transport level to another tower to make a connection.*
- *Connect a skybridge*
- *This city has all 32 skybridge connections.* — once you hit the cap,
  no more skybridges can be added.

### Lifts
- *Install lift bank* — adds an elevator.
- *Three lift banks are installed* — the cap for most towers.
- *Lift banks closed to new departures* — pause and resume.

## Annexes

Many buildings accept **annexes** — extra structures attached to the side
of the main building. Annexes add capacity or an operating effect.

> *Each annex adds its listed capacity or operating effect.*

Common annexes include:

- **Treatment wing** — adds hospital capacity.
- **Detention wing** — adds police detention places.
- **Sixteen additional detention places. Does not add patrol cars.**
- **Two additional ambulances. Treatment places stay unchanged.**
- **Six additional garage bays. Purchase the actual streetcars in the
  line editor.**
- **Two additional school buses. Classroom capacity stays unchanged.**
- **Two additional fire engines with their own dispatch and return trips.**
- **Two additional police cars. Detention capacity stays unchanged.**
- **Two additional collection trucks. Processing and storage stay
  unchanged.**

### How to add an annex
- *Select an existing compatible facility before adding an annex.*
- *Attach the annex to the highlighted building · R to rotate*
- *Place the annex directly against a side of its main building.*
- *This site already has six annexes.* — most sites have a cap.

### Annex warnings
- *Building footprints overlap.* — back up and try again.
- *Flatten the annex site to meet the main building.*
- *Site annex limit reached*

## Demolishing

- *Bulldozer · B* — the universal tool. Drag to clear a building, road,
  zone, or tree.
- *Demolishing the main building clears the whole site.* — annexes go
  with the main building.
- *Confirm level demolition* — confirms a paid level demolition.
- *Confirm whole tower demolition* — confirms the whole tower.

## Building condition

Buildings can be **damaged** by disasters and **abandoned** if you don't
repair them.

- *A building record is damaged.*
- *Abandoned — repair or redevelop*
- *Abandoned · restore this building*
- *Repairs can suffer further damage while this site remains under
  water.*
- *Repair · $X* — the cost to fix it.
- *Needs repair or fire response*

> *Building condition* is a data layer. See
> [The data layers](part-6-tools/the-data-layers.md).

## Tips & common pitfalls

- **Roads, power, and water.** Most buildings need all three. Check the
  building card before placing.
- **Tall buildings want transit.** Office towers without a transit
  connection end up full of cars.
- **Annexes count.** A site with six annexes is at its cap. Plan ahead.
- **Skybridges are precious.** Each city has a hard cap of 32.
- **Don't bulldoze a working building.** Use **Temporarily close** if
  you want to pause it.

## Related pages

- [Districts and policies](districts-and-policies.md) — paint a district
  to set local rules.
- [Public transit](part-3-utilities/public-transit.md) — bus depots,
  streetcar depots, metro, maglev, and rail.
- [Great works](part-5-simulation/great-works.md) — the biggest builds.

---

### Screenshots to capture
- ![alt: The build menu open on the right side of the screen. Categories in a vertical list: Power & industry, Water & agriculture, Waste & recycling, Public safety, Schools & learning, Transit & freight, Commercial, Parks & leisure, Great works. The Public safety category is selected, showing fire station, police station, clinic, hospital, school bus garage, and patrol garage cards.](../../assets/images/build/buildings-menu.png "The build menu — Public safety category")
- ![alt: A tower with its editor open. The podium is at the base, four paid levels are stacked above, and a roof crown (an observation deck) sits on top. The level catalog is on the right, showing available level types. A "Finish the tower podium" warning is at the top of the editor.](../../assets/images/build/buildings-tower-editor.png "The tower editor — podium, four levels, and a roof crown")
- ![alt: A hospital with two annexes: a treatment wing on one side and a detention wing on the other (this is the police station from the other photo — corrected to a clinic with a treatment wing). The annex footprint is visible, with a small label "Treatment wing."](../../assets/images/build/buildings-annex.png "A hospital with two annexes")
- ![alt: A damaged building. The roof is partially collapsed, smoke wisps rise from the windows, and a red warning icon floats above. A repair panel reads "Repair · $1,250 · 2 days."](../../assets/images/build/buildings-damaged.png "A damaged building in need of repair")
- ![alt: The skybridge editor. Two towers are connected by a skybridge at level 5. The skybridge has its own transport level selector. A note at the top reads "Add a Skybridge transport level to another tower to make a connection."](../../assets/images/build/buildings-skybridge.png "A skybridge connecting two towers")
