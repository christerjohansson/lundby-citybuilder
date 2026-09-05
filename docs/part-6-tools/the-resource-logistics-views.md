# The resource logistics views

> *Manage resource logistics*

The resource logistics views are the live reports on the city's
freight — every load, every carrier, every cargo route, every receipt.
This is where you go when a delivery is late, a warehouse is full, or
a trade route needs rebalancing.

## Where to find them

- **City → Resource logistics → Resource logistics views**

> *Resource logistics views* — the section.
> *Manage resource logistics* — the link.

## The five views

### 1. This city's cargo

- *This city's cargo* — the in-city stock.
- *Cargo aboard* — the in-transit counter.
- *Goods in stock* / *Goods held in the city* — the inventory.
- *Goods in delivery trucks* — the in-transit stock.
- *Goods per staffed position* — the per-worker productivity.
- *Source:* / *Goods source* / *Commodity* / *Material* — the
> filters.
- *Delivered each day* / *Delivered to buildings* / *Delivered to
> factories* — the daily outputs.
- *Recent deliveries* / *Recent shipments* / *Recent cargo receipts*
> / *Recent customer activity* — the live log.
- *No deliveries match this filter.* — the empty state.
- *No recent customers* / *No recent shipments* — the variants.

### 2. Resource logistics views

- *Filter resource deliveries* / *Filter resource facilities* — the
> filters.
- *Search resource deliveries* / *Search resource facilities* / *Find
> a factory* / *Find a workplace or home* — the search.
- *Next resource page* / *Previous resource page* — the paging.
- *Recent shipment activity* — the live log.
- *Statement period* / *Resource reporting period* — the period
> labels.
- *Resource export sale* / *Resource import purchase* / *Resource
> freight charge* — the lines.
- *Recorded* / *All recorded time* / *All time* — the cumulative
> labels.
- *Since freight records began* — the long-term line.
- *Last completed shift* — the daily output.

### 3. Resource facilities

- *Filter resource facilities* — the filter.
- *Search resource facilities* — the search.
- *Resources* / *Resource store* / *Resources* — the facility
> types.
- *Service building* / *Service accounts* — the lines.
- *Service per staffed position* — the productivity.
- *Working / positions* / *Currently reachable staff* / *Required
> staff* — the staffing.
- *Attending staff* / *Attending assembly workers* — the workforce.
- *Available service fleet* — the fleet.
- *Garage bays* / *Fleet berths* / *Loading bays available* — the
> capacity.
- *Loading siding* / *Loading bays available* — the loading
> capacity.
- *Waiting for a physical loading siding* / *Waiting for a physical
> terminal siding* — the wait state.

### 4. Plan a shipment

- *Plan a shipment* — the planner.
- *Plan a development project* — the development variant.
- *Plan a shipment* — the action.
- *Choose a load and route between actual stores.* — the rule.
- *Choose a positive load between different stores* — the rule.
- *Choose a finite, positive shipment* — the rule.
- *No unbroken road connects these stores* — the failure.
- *No available factory can deliver by road* — the failure.
- *No reachable warehouse has receiving space* — the failure.
- *No reachable local supplier has unreserved materials* — the
> failure.
- *No matching factories in this network.* — the empty state.
- *The city’s material carriers are all assigned* — the wait state.
- *The city's material carriers are all assigned* — the variant.
- *The factory's private reserve cannot cover inputs and freight* —
> the cash failure.
- *The shop's purchasing reserve cannot cover goods and freight* —
> the variant.
- *The loading warehouse needs an unbroken road to the regional
> boundary* — the regional rule.
- *The receiving warehouses have no unreserved storage space* — the
> warehouse failure.
- *The receiving warehouse closed; cargo remains aboard* — the
> closed-receiver failure.
- *The receiving terminal full; the remaining cargo stays aboard* —
> the variant.
- *The receiving store full; remaining cargo stays aboard* — the
> variant.
- *The input reserve is full or already on the way* — the input
> variant.
- *The selected reserve is full or already on the way* — the variant.
- *The reserve is full or already on the way* — the variant.
- *The catalyst reserve is full or already on the way* — the
> variant.
- *The remaining fare allowance cannot cover boarding* — the
> passenger variant.
- *The remaining ticket allowance cannot cover this train* — the
> rail variant.
- *The remaining visit ·* — the visitor variant.

### 5. Trade

- *Trade mode* / *Open resource trading* / *Region & trade* — the
> links.
- *Manage resource logistics* — the link.
- *Track regional deliveries* — the link.
- *Offer this city's surplus* / *Offer local control capacity* —
> the sell actions.
- *Found a region to exchange control capacity between your cities.*
> — the offer.
- *Regional control market* / *REGIONAL CONTROL EXCHANGE* — the
> exchange.
- *Regional control capacity purchased* / *Regional control capacity
> sold* — the lines.
- *Regional control allocation did not reserve its complete request.*
> — the partial-fill warning.
- *Purchase from your neighbors* / *Automatic regional trading* —
> the buy actions.
- *Paid regional control purchases* / *Paid regional control sales*
> — the lines.
- *Save control offer* / *Uncommitted offer now* / *Update the offer
> details* — the actions.

## Specific reports

### Factories
> *Factories* / *Factory* / *Factory closed* / *Factory not
> operating* / *Former factory* — the factory states.
> *Factory delivery* / *Factory input purchases* / *Factory purchase
> returns* / *Factory loading store is full* / *Factory closed; paid
> cargo waits at its loading bay* / *Factory closed; paid materials
> are held at its loading bay* — the delivery states.
> *No available factory can deliver by road* — the failure.
> *Two paid loads are already assigned to this factory* — the
> conflict.
> *The factory must be open, supplied with utilities, and connected
> by road* — the prerequisites.
> *The factory needs attending workers before ordering catalyst* —
> the workforce requirement.
> *The factory's private reserve cannot cover inputs and freight* —
> the cash requirement.
> *The factory needs working roads, utilities and a completed
> building* — the building requirements.
> *The factory no longer uses this material; recall the remaining
> load* — the obsolete material warning.
> *The loading store's delivery fleet is busy* — the wait state.
> *Recall load* / *Cancel order* — the actions.
> *Recall the remaining load* — the action.
> *Recall load* — the variant.
> *Refunded on arrival* — the refund timing.
> *Carrier recalled. Remaining cargo must return before its refund
> is paid.* — the warning.
> *Truck recalled. Cargo is refunded after its return.* — the
> road-freight variant.
> *Wait for active cargo vehicles to return before selling them* —
> the asset warning.

### Shops
> *Shops* / *Shop could not serve this trip* / *This shop's import
> trucks are on the road* — the shop states.
> *Bring the daily shop closer* — the warning.
> *The shop must be repaired and complete* — the prerequisite.
> *The shop's purchasing reserve cannot cover goods and freight* —
> the cash rule.
> *Two deliveries are already assigned to this shop* — the conflict.
> *Cancel order* / *Plan a shipment* — the actions.

### Cargo
> *Cargo and freight paid; stock becomes usable on arrival.* — the
> settlement timing.
> *Cargo paid / carrier fee* — the invoice.
> *Cargo aboard* / *Ordered / aboard* — the state.
> *Approaching the receiving warehouse* / *At factory* / *At the
> destination* / *Back at base* / *Back at supplier* — the
> in-transit status.
> *Returning empty* / *Returning to the loading store* / *Returning
> with waste* — the return.
> *Still aboard* / *Still on land* / *Unloaded* / *Unloaded · ready
> to return* / *Unloading* / *Unloading · waiting for tank space* —
> the unload state.
> *Delivered* / *Delivered / sent* — the completion.
> *Returned* / *Returned-load refunds* / *Returned factory cargo
> refunds* / *Returned factory materials* / *Returned import refunds*
> / *Returned input refunds* / *Returned local / imported cargo* /
> *Returned resource refund* / *Returned to open water* — the return
> lines.
> *Returned catalyst cargo refunds* / *Returned catalyst cargo* — the
> catalyst variant.
> *Cargo refund* / *Cargo returned* / *Cargo refunds received* — the
> refunds.
> *Carrier returned* / *Carrier recalled* — the carrier states.
> *Empty return to supplier* — the empty return.
> *Empty storage* / *Empty return to supplier* — the empty state.
> *Finished catalyst store full* / *Finished-goods store full* /
> *Landfill storage* / *Full storage* / *Storage full* — the
> storage states.
> *Loading* / *Loading store* / *Loading bays available* / *Loading
> siding* — the loading state.
> *Receiving store* / *Receiving store full* — the receiving state.
> *Shipment commodity* / *Shipment loading store* / *Shipment
> receiving store* / *Shipment requested quantity* / *Shipment
> transport* / *Shipment unavailable* — the shipment fields.
> *Supply interrupted* / *Supply chain interrupted* — the
> interruption.
> *Locate collection truck* / *Locate fire engine* / *Locate work
> connection* / *Locate and inspect building* / *Locate works* —
> the locate actions.

### Fuel
> *Fuel* / *Fuel source* / *FUEL RESERVE* / *Fuel reserve yard* —
> the fuel facilities.
> *Fuel burned to date* / *Fuel controls* / *Fuel on the road* /
> *Fuel on the way* / *Fuel depleted* / *Fuel reprocessing annex* /
> *Fuel truck* — the fuel states.
> *A fuel delivery is blocked.* — the failure.
> *Both delivery trucks are on the road; wait for a return* — the
> wait state.
> *Both factory delivery contracts are away; wait for a carrier to
> return* — the variant.
> *Stockpile this fuel in the industry warehouse or allow imports* —
> the policy choice.
> *The quoted fuel store no longer owns this load* — the load
> mismatch.
> *A generator is low on fuel* — the warning.
> *Repair and finish the plant before ordering fuel* — the
> prerequisite.
> *Sent as power-plant fuel* — the use.
> *Generation would burn more fuel than the plant owns* — the
> capacity warning.
> *Returned unused fuel* — the return.
> *Lifetime fuel conservation* — the research effect.
> *Reactor fuel* — the nuclear fuel.

### Materials and inputs
> *Material accounts* / *Material* / *Materials* / *Material
> carrier #* / *Material carriers assigned* / *Material source* —
> the material state.
> *Input storage* / *Input reserve* / *Input bay full* — the input
> state.
> *Processing inputs used* / *Processing / intake capacity* — the
> processing line.
> *Consumed by production* / *Dispatch available materials* — the
> consumption.
> *Sourced material* / *Sourcing material* — the action.
> *Invalid private material quantity* / *Invalid private material
> account* — the errors.
> *Lost with removed stores* / *Lost with demolished input stores* —
> the loss.
> *Primary materials in private ownership* — the ownership state.
> *Reserved for the refit* / *Private reserve for the refit* — the
> refit.
> *Accounted material* / *Accounted material quantities* — the
> accounting.
> *Committed capital* / *Allocated to this city now* — the
> commitments.

### Production
> *Production* / *Production operating* / *Works processing / day* —
> the production state.
> *Stock & sell treated goods* / *Treated goods in store* / *Stockpile*
> — the stock.
> *Inputs ·* / *Output store* — the inputs and outputs.
> *No purchase made* — the empty state.
> *No recent activity* — the variant.
> *Production* / *Manufacturing* — the section.
> *Advanced manufacturing* / *Basic manufacturing* — the tiers.
> *The catalyst reserve is full or already on the way* — the
> catalyst state.
> *Order catalyst* / *Produce catalyst* / *Paid catalyst delivery on
> the way* / *Catalyst in store* / *Catalyst works* / *Catalyst
> works expanded* / *Catalyst reserve* / *Catalyst delivery trucks* /
> *Catalyst load* / *Catalyst sale* / *Catalyst sales this month* /
> *Catalyst sold to a private factory* / *Catalyst sold to private
> factories* — the catalyst lines.

## Tips & common pitfalls

- **The resource logistics view is the source of truth.** If a
  delivery is late, it's here.
- **Filters hide data.** A filter that hides everything is often the
  cause of a missing delivery.
- **The cash reserves matter.** *The factory's private reserve cannot
> cover inputs and freight* is the most common failure.
- **Recalls are slow.** A recalled truck has to physically return
  before the refund posts.

## Related pages

- [Commerce and shoppers](part-5-simulation/commerce-and-shoppers.md)
  — what the freight is for.
- [Rail and ports](part-3-utilities/rail-and-ports.md) — the
  infrastructure.
- [Regional cities](part-5-simulation/regional-cities.md) — the
  trade partners.

---

### Screenshots to capture
- ![alt: The resource logistics view. A list of in-transit cargo loads: a delivery from a coal mine to a power plant, a load of metal from a metalworks to a factory, a return trip from a shop to a depot. Each row shows the commodity, the quantity, the carrier, the status, and the source/destination.](../../assets/images/tools/resource-cargo.png "The resource logistics view")
- ![alt: A factory in production. A "Factory delivery" panel shows the inputs (80 ore, 35 coal) and the outputs (65 metal). A "Recent shipments" log lists the last five deliveries. A "Stockpile this fuel in the industry warehouse or allow imports" toggle is visible.](../../assets/images/tools/resource-factory.png "A factory in production")
- ![alt: The plan a shipment dialog. A "from store" picker, a "to store" picker, a commodity picker, a quantity field, and a "Plan" button. A "No reachable local supplier has unreserved materials" warning is visible because the source store is empty.](../../assets/images/tools/resource-plan.png "The plan a shipment dialog")
