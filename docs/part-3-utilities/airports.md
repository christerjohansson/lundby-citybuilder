# Airports

> *A gateway connecting the entire region to the world.*

Airports connect your city to the rest of the world. They handle
passenger flights, cargo flights, and the manufacturing and operation
of the aircraft that fly from them.

## The airport system

Lundby's airports are full systems, not single buildings. Each airport
has:

- A **runway** for takeoffs and landings.
- A **terminal** for passengers and cargo.
- **Passenger gates** for boarding.
- A **fleet** of aircraft.
- Optionally, an **assembly works** for manufacturing aircraft.
- A **headquarters** for managing the airline.

> *Put your city on the map.*

## Building an airport

### Step 1 — Place the runway
1. Open the **Airports** tool and pick **Runway**.
2. *Build airport* — pick a direction and length.
3. The runway needs a long, flat site.

> *Fog: upgrade to level 2 for instrument approaches.* — the message
> you see when the airport can't operate in fog.

### Step 2 — Place the terminal
1. Pick **Terminal** from the airports tool.
2. *Attach passenger gates behind the terminal, away from the
> runway.*
3. *Attach passenger gates on clear land behind the terminal, away
> from the runway.*

> *Passenger gate* — the small structure that holds the aircraft.

### Step 3 — Connect the airport
1. Build a road from the terminal to a regional road.
2. *Connect the airport to regional roads.*
3. Add **power and water** to the terminal.
4. *Restore airport electricity and water.*

> *Airport operations* — the management menu section.

### Step 4 — Add a headquarters
1. Place an **Airline headquarters** near the terminal.
2. *Build a corporate headquarters before opening a catalyst works.* —
> the prerequisite for some annexes.
3. *Needs attending staff, utilities and an operating level-two
> headquarters.* — the requirement for higher-tier operations.

## Aircraft

Aircraft come in three families:

- **Turboprop** — short-haul passenger and small cargo.
- **Regional jet** — medium-haul passenger.
- **Airliner** — long-haul passenger and large cargo.

> *Aircraft in service* — the fleet status.
> *Aircraft lost* — the all-time counter.
> *Service life completed* — when a retired aircraft is sold.

### Buying a fleet
> *Choose a fleet between 1 and 20 vehicles.*
> *Choose a fleet that fits this terminal's bays.*
> *Not enough funds to buy these vehicles.* — the warning when the
> treasury is short.

### Retiring a fleet
> *Retire one vehicle* — sells one aircraft for half its purchase
> price.
> *Automatic fleet target met. Aircraft on missions remain assigned
> to this base.* — the autopilot message.

## Flights

### Passenger flights
*Passenger flights*

- Open the **flights panel** and create a route.
- *Choose an existing airport and a destination.*
- *This airline connection already exists.* — the warning for a
> duplicate.
- *Passenger flights* — the line item.
- *Landings / requests* — the daily counter.
- *All-time arrivals / departures* — the all-time counter.

> *Runway open · flight services available* — the status when
> everything is online.
> *Ground hold: fog requires instrument approaches* — the warning
> when fog grounds flights.
> *Ground hold: repair and finish the airport* — when the airport is
> under construction.
> *Ground hold: runway inundated by floodwater* — when the runway
> is flooded.

### Cargo flights
*Cargo flights*

- A separate fleet for cargo.
- *Cargo paid / carrier fee* — the invoice.
- *Cargo and freight paid; stock becomes usable on arrival.* — the
> settlement timing.

### Airline agreements
*Airline agreements*

- *Open airline management* — the management menu item.
- *Airline agreement signed · <date>* — the confirmation.
- *Not enough funds for this airline agreement.* — the warning.
- *Operated air-service contracts* — the report.

## Manufacturing aircraft

A high-tier airport can include an **assembly works** that manufactures
aircraft.

> *Manufactured · awaiting commissioning*
> *Manufactured · retired · lost*
> *Manufactured · today*

The assembly works needs:

- **Assembly materials** — delivered by road.
- **Aircraft assembly storage** — for finished aircraft.
- **Attending assembly workers** — to operate the line.

> *Deliver assembly materials and let your workers manufacture the
> first aircraft.*
> *Manufactured aircraft* — the daily output.
> *Assembly work in progress* — the status.
> *Assembly works · <name>* — the works' name.
> *Assembly storage* — the storage facility.

## Drone bases

A separate but related system: **drone bases** for manufactured
service drones (fire, police, medical).

> *Drone bases* — the management menu item.
> *Place a drone hangar · $6,500* — the build card.
> *Add an emergency hangar* — the annex.
> *Build a receiving base first* — the prerequisite.
> *Drone manufacturing* — the management section.
> *Manufactured drone fleet* — the fleet panel.
> *Manufactured drone in flight to this base* — the in-transit
> status.
> *Drone commissioning is included in the posted totals above.* —
> the accounting note.
> *Manufactured drone commissioning* — the report line.
> *A drone exhausted its battery before reaching a safe landing
> point* — the worst-case log entry.
> *A drone is collecting a reserved basket from the shop* — the
> shopping drone status.
> *No commissioned drone or safe household landing point is
> available* — the failure case.
> *Stored drones were lost with the removed hangar* — the warning
> if a base is demolished with aircraft inside.
> *Drone #<id> is flying to the assigned base.* — the typical
> status.

## Airport reports

The **AIRPORTS & AIRLINE CONNECTIONS** panel shows:

- *Active flights* — the live board.
- *Aircraft filter* — by type or status.
- *Aircraft in service* / *Aircraft lost* — the fleet.
- *Completed flight cycles* — the all-time counter.
- *Earned airport passenger fees* — the day's revenue.
- *Airport passenger fees* — the line item.
- *Airport visitor fee* — the per-passenger charge.
- *Airline service costs* — the operating cost line.
- *Cargo fleet purchase or sale* — the asset line.
- *Cargo fleet purchased* — the confirmation.

## Tips & common pitfalls

- **A long runway is a big investment.** Start with a short runway and
  upgrade.
- **Gates are the bottleneck.** A terminal with three gates can handle
  three flights at once.
- **Manufacturing is optional.** Most cities buy aircraft, not build
  them.
- **Fog grounds flights.** The *Fog: upgrade to level 2* message means
  the airport needs an instrument-landing upgrade.
- **Floods close the runway.** *Airport inundated by floodwater.* —
  the warning.
- **Cargo flights are a separate fleet.** Don't try to fly passengers
  and cargo with the same aircraft.

## Related pages

- [Public transit](public-transit.md) — the surface side of the
  network.
- [Rail and ports](rail-and-ports.md) — the freight side.
- [The data layers](part-6-tools/the-data-layers.md) — the airspace
  layer.

---

### Screenshots to capture
- ![alt: A small regional airport on a flat site beside the coast. A single runway runs north-south. A terminal with three gates is at the south end. A control tower is visible. Two regional jets are parked at gates, and a turboprop is on approach.](../../assets/images/utilities/airport-overview.png "A small regional airport")
- ![alt: The airports management panel. An airline agreement is open: a route from this airport to a destination 800 km away, with two daily round trips on a regional jet. A "Passenger flights" schedule is visible, and a small chart shows daily boardings.](../../assets/images/utilities/airport-flights.png "An airline agreement")
- ![alt: A terminal interior view from the gate. A regional jet is at the gate with its door open. Passengers are walking down the jet bridge. A "Flight held" status is visible on the panel.](../../assets/images/utilities/airport-gate.png "A gate in operation")
- ![alt: An aircraft assembly works. A half-built aircraft is in the bay. A delivery truck is unloading assembly materials. A counter reads "Assembly work in progress — 60 %."](../../assets/images/utilities/airport-assembly.png "An aircraft assembly works")
- ![alt: A drone base on a rooftop. Three small drones are on the charging pad. A "Manufactured drone fleet" panel in the corner shows 3 in service, 1 charging, 0 lost.](../../assets/images/utilities/airport-drone-base.png "A drone base")
