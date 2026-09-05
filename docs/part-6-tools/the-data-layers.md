# The data layers

> *Data layers* / *Map category colors*

The data layers are the map overlays that show the simulation's state
on the city map. They turn the 3D world into a debugging tool: you
can see at a glance where the power is connected, where the water is
clean, where the response time is slow, and where the wealth is.

## Where to find them

- **City → Data layers**
- Or click the data layer button in the toolbar.

> *Data layers* — the section.
> *Map category colors* — the legend.
> *Map category colours* — the variant.

## The data layers

### Electricity
**Show electricity map** / **Hide electricity map**

> *Green means connected to a working electricity supply.*
> *Some homes need power.* — the warning.
> *No electricity* — the disconnected state.
> *Power reaches* / *Power connected* — the connection.
> *Restore electricity.* — the recovery hint.
> *Power connected* / *Electricity needed* — the report.

### Water
**Show water map** / **Hide water map**

> *Green building lots receive clean water. Orange means contamination
> or no supply.*
> *Clean water needs attention.* — the warning.
> *Drinking water is contaminated* / *Imported drinking water* — the
> state.
> *Some taps are running dry.* — the warning.
> *Water needed* / *Water connected* / *No water supply* — the
> connection.
> *Restore the water supply.* — the recovery hint.
> *Water supply under pressure* — the warning.
> *Delivered water quality* / *Untreated source quality* — the
> quality.
> *Drinking-water quality* — the report.
> *The groundwater and water-quality records are damaged.* — the
> error.

### Waste
**Show waste map** / **Hide waste map**

> *Waste awaiting pickup* — the icon.
> *Waste collection* — the section.
> *Waste & recycling* — the report.
> *Recovers collected waste* — the recovery plant description.

### Response
**Show response map** / **Hide response map**

> *Reduce disaster damage and speed up fire response.* — the
> research effect.
> *Average response, all services* — the metric.
> *Station location, funding, utilities, and road access determine
> your response.* — the rule.
> *Calls not resolved in time* — the counter.
> *The civic response record is damaged.* — the error.

### Surface buildings
**Hide surface buildings to see tunnels, transit lines and stations.**

A special toggle: hides the surface buildings to expose the metro
tunnels, the underground utilities, and the lower levels of the
towers.

> *Hide surface buildings to see tunnels, transit lines and
> stations.* — the description.

### Control
**Show control coverage** / **Hide control coverage**

> *CITY CONTROL NETWORK* — the section.
> *Control coverage* — the report.
> *No operating control source covers this site.* — the failure.
> *Utilities cannot support this control source.* — the failure.
> *Signal sources* / *Signal radius* — the sources.
> *Distributed control* / *Control center* / *Control network* —
> the network.
> *Control capacity* / *Staffed control capacity* / *Control
> capacity allocated* / *Insufficient control capacity. Adjust
> priorities or add staffed sources.* — the capacity.
> *Every maglev station needs water and its full control allocation*
> — the rule.
> *The institute and control-network record is damaged.* — the
> error.

### Learning access
**Show learning access map** / **Hide learning access map**

> *Learning access from available classrooms, school routes, and
> libraries.* — the description.
> *Connected workforce education* — the metric.
> *Every eligible student can reach a classroom. Keep room for the
> next generation.* — the rule.

### Franchise
**Show franchise map** / **Hide franchise map**

> *Franchise active* / *Franchise type* / *Franchise addresses* —
> the data.
> *Corporate franchises* / *Supplied franchises* — the network.

### Retail wealth
**Show retail wealth map** (no separate toggle in the layer menu)

> *Retail wealth* / *Retail wealth map* — the report and overlay.
> *Share of the nearby customer base* — the metric.

### Technology
**Show technology map**

> *Technology map* / *Technology* — the overlay.

### Building condition
> *Building condition* — the layer.
> *Building condition* / *Building fire and atmospheric emissions* —
> the report.

### Traffic congestion
**Show traffic congestion** (or similar)

> *Traffic congestion* / *Traffic* — the layer.
> *Traffic direction* / *Street direction changes* / *One-way street
> arrows* — the road state.

### Pollution
> *Pollution* — the layer.
> *Industrial air & soil emissions* — the report.
> *Ground pollution* / *Air pollution* — the lines.
> *Green is clean air. Orange is higher pollution.* — the legend.
> *Move heavy industry away from homes and add parks or clean
> industry standards.* — the advice.

### Land value
> *Land value* — the layer.
> *Green areas have the highest land value.* — the rule.
> *Green space raises land value and absorbs pollution.* — the rule.

### Income groups
> *See income groups on the map* — the toggle.
> *Slate: lower income. Green: middle income. Gold: affluent
> households.* — the legend.
> *Income groups* — the report.

### Aquifer
> *Green is a full aquifer. Orange is depleted ground. Wells share
> nearby reserves.* — the legend.

### Surface buildings (hide)
> *Hide surface buildings to see tunnels, transit lines and
> stations.* — the description.

### Saved data
> *Clear data overlay* — the action.
> *Data layers* — the section.

## The data layer legend

Every layer has a small legend in the corner of the map. The legend
tells you what the colours mean.

> *Map category colours* — the legend.
> *Map category colors* — the variant.
> *Clear data overlay* — the action.

## Tips & common pitfalls

- **Layers can be combined.** Show the water map and the electricity
  map at the same time to see the whole utility network.
- **Some layers require the right tools.** *Hide surface buildings*
  needs the planning camera to be useful.
- **The legend is in the corner.** If you don't know what a colour
  means, look at the legend.
- **Layers are a debugging tool.** They show the simulation's state,
  not the city's appearance.

## Related pages

- [The management menu](the-management-menu.md) — where the layers
  are toggled.
- [Power grid](part-3-utilities/power-grid.md) — the electricity
  layer.
- [Water](part-3-utilities/water.md) — the water layer.
- [Population and households](part-5-simulation/population-and-households.md)
  — the income groups layer.

---

### Screenshots to capture
- ![alt: The data layer menu open on the right side of the screen. A list of toggles: Electricity, Water, Waste, Response, Control, Learning access, Franchise, Retail wealth, Technology, Building condition, Traffic congestion, Pollution, Land value, Income groups, Aquifer. The Electricity and Water layers are on.](../../assets/images/tools/data-layers-menu.png "The data layer menu")
- ![alt: The map with the electricity and water layers active. Buildings are coloured: green for both utilities connected, orange for one connected, red for neither. A "Green means connected to a working electricity supply" legend is in the corner.](../../assets/images/tools/data-layers-utilities.png "Electricity and water layers")
- ![alt: The map with the response and traffic congestion layers active. Buildings are coloured by response coverage (green / orange / red) and roads are coloured by congestion (green / orange / red). Two legends are visible: "Average response, all services" and "Traffic congestion."](../../assets/images/tools/data-layers-response.png "Response and traffic layers")
