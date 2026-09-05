# Public transit

> *Give people somewhere to go, a way to get there, and a place to spend the night.*

Public transit is how a city of any size moves. Lundby has six modes:
buses, streetcars, the metro, maglev, commuter rail, and ferries. Each
has its own infrastructure, vehicles, and operating rules.

## Buses

*Operates bus services between stops, reducing car traffic.*

The simplest mode. Place stops near homes and jobs, draw a route, and
add a bus depot.

### How to set up a bus line
1. Open the **Transit** tool and pick **Bus stop**. Place stops near
   homes and jobs.
2. Open the **Line editor** and pick **Bus route**.
3. Click the stops in order. The line follows the road between them.
4. Open the **Bus depot** and assign vehicles to the line.

> *Place stops near homes and jobs, then add them here.*
> *Connect an operating bus depot to these stops*
> *A city can operate up to 16 transit lines.* — the per-city cap.

### Bus reports
- *Buses assigned / available* — the depot status.
- *Bus routes* — the line list.
- *ESTIMATED INTERVAL* — the headway between buses.
- *Passenger fares collected* — the revenue line.
- *Public transport use* — the citywide share.

## Streetcars

*Operates bus services between stops, reducing car traffic.* (The
description is similar; streetcars run on tracks along avenues.)

Streetcars are the workhorse of a mid-sized city. They run on tracks
laid on top of avenues, and they're cheap to run once the tracks are
in.

### How to set up a streetcar line
1. Build an **avenue** where you want the line.
2. *Build an avenue before adding streetcar tracks.*
3. Open the **Transit** tool and pick **Streetcar tracks**. Lay tracks
   on the avenue.
4. *Connect avenue tracks beside every streetcar stop.*
5. Place **Streetcar stops** along the avenue.
6. *Connect a powered streetcar depot to this track network.*
7. *Connect a streetcar depot with available bays.*
8. Create a **Streetcar line** in the line editor and add the stops in
   order.
9. *Purchase the actual streetcars in the line editor.*

> *Lay avenue tracks*

### Streetcar reports
- *Streetcar garage bays* — the depot capacity.
- *Streetcars dispatched* — the active fleet.
- *Line color* — the line's colour in the editor and on the map.

## Metro

*Metro station* / *Metro tunnel*

The metro is the high-capacity underground. It's expensive to build
but very fast and very high-capacity.

### How to set up a metro line
1. Pick the **Metro tunnel** tool.
2. Draw a tunnel under the city. *Connect metro tunnels beneath or
> beside every station.*
3. Place **Metro stations** along the tunnel.
4. *Each station needs its own platform along the railway.*
5. Build a **Metro depot** to host the trains.
6. Create a **Metro line** in the line editor.

> *Draw tunnels*

## Maglev

*Elevated guideway* / *Maglev station* / *Maglev depot*

Maglev is the elevated high-speed mode. It runs on a guideway above
the city.

### How to set up a maglev line
1. Pick the **Elevated maglev guideway** tool.
2. Draw a guideway across the city. *Connect an elevated guideway
> directly beside every maglev station.*
3. Place **Maglev stations** along the guideway.
4. *Connect a maglev depot with power, water and control capacity to
> this guideway.*
5. Build a **Maglev depot** to host the trains.
6. *Every maglev station needs water and its full control allocation.*
7. Create a **Maglev line** in the line editor.

> *Draw elevated guideway*
> *Keep the elevated guideway clear of buildings and annexes*
> *Keep the elevated guideway corridor clear*

## Commuter rail

*Commuter trains* / *Rail station*

Commuter rail is the regional heavy rail. It connects your city to the
region.

### How to set up a commuter rail line
1. Build a **Rail depot** beside a connected road.
2. *Connect an operating rail depot with straight, level railway along
> its full side.*
3. Lay surface railway to the **Rail station** on the edge of the map.
4. *Connect a station to the edge of the map for regional passenger
> service.*
5. Create a **Commuter rail line** in the line editor.

> *By commuter rail*

## Ferries

*Ferry terminal* / *Passenger ferries*

Ferries are the water-based mode. They connect piers and islands, and
they're how regional passenger service works over water.

### How to set up a ferry line
1. Build a **Ferry terminal** beside open water.
2. *Every ferry terminal needs an open water berth.*
3. *Restore an open water edge beside this quay.*
4. Build another **Ferry terminal** at the other end.
5. *Connect a station to the edge of the map for regional passenger
> service.*
6. Create a **Ferry line** in the line editor.

> *By ferry*

## The line editor

Every line is managed in the line editor. The line editor is where you:

- Name the line and pick its colour.
- Add and remove stops.
- Set the **stop order**.
- Set the **headway** (the time between vehicles).
- Set the **fare**.
- *Choose a fleet between 1 and 20 vehicles.*
- *Passenger fleet purchase* — buy the vehicles for the line.
- *Operate this line* / *Service paused* — toggle service.
- *Pause the current project before starting or moving another.*

> *A city can operate up to 16 transit lines.*

## Transit reports

The **CITY TRANSIT** panel (under *Transport & routes*) shows:

- **Lines** — every line, with its stops and headway.
- **Fares paid / held** — the day's revenue.
- *Public transport use* — the citywide share.
- *Blocked journeys only* — filter to see only the broken ones.
- *Completed / unsuccessful trips* — the day's outcomes.
- *Workers promoted* — the link between transit and education.

## Transit effectiveness

> *Double transit effectiveness and improve happiness.* — the impact
> of a strong transit network.

> *Reach 30 % public transport use.* — a milestone you'll see when
> transit is carrying a real share of journeys.

## Tips & common pitfalls

- **Match the mode to the demand.** A bus is enough for a small
  neighborhood; a metro is needed for a downtown.
- **Stops are cheap; lines are cheap; vehicles are not.** The depot
  and the fleet are where you spend.
- **Headway is the lever.** A 5-minute headway costs more than a
  15-minute headway.
- **Fares pay for service.** Set them too high and ridership falls;
  set them too low and you can't afford the fleet.
- **A broken line is worse than no line.** A bus that doesn't run
  teaches residents that transit is unreliable.

## Related pages

- [Roads](part-2-build/roads.md) — the road network that buses and
  streetcars run on.
- [Rail and ports](rail-and-ports.md) — the freight side of the
  network.
- [Airports](airports.md) — the air side.

---

### Screenshots to capture
- ![alt: A bus line in a residential neighborhood. Three bus stops are placed along a local street. A bus depot is at one end. The line editor is open, showing the stop order and a 10-minute headway.](../../assets/images/utilities/transit-bus.png "A bus line in a residential neighborhood")
- ![alt: An avenue with embedded streetcar tracks. Two streetcars are visible, one at each end of a four-stop line. A streetcar depot is in the middle. The line editor is open, showing the line colour (orange) and a 6-minute headway.](../../assets/images/utilities/transit-streetcar.png "A streetcar line on an avenue")
- ![alt: A metro station entrance in a downtown plaza. The metro tunnel runs beneath the avenue. A train is visible in the station. The line editor shows a 4-minute headway and 18 000 daily boardings.](../../assets/images/utilities/transit-metro.png "A metro station")
- ![alt: A maglev guideway crossing the city on elevated pylons. Two maglev trains are visible, one arriving and one departing. A maglev depot is in the foreground, and a maglev station is in the background.](../../assets/images/utilities/transit-maglev.png "A maglev guideway and trains")
- ![alt: A ferry terminal on a pier. A passenger ferry is at the dock, and another is approaching from across the bay. A second ferry terminal is visible on a nearby island. The line editor shows a 20-minute headway.](../../assets/images/utilities/transit-ferry.png "A ferry terminal and two ferries")
- ![alt: The line editor with a complex streetcar line. The line has 11 stops, a custom name, an orange line colour, a 5-minute headway, and 24 000 daily boardings. A "Service paused" toggle is visible.](../../assets/images/utilities/transit-line-editor.png "The line editor — a complex streetcar line")
