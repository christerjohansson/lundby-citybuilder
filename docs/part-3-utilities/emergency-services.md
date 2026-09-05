# Emergency services

> *When every moment matters.*

Emergency services keep your city safe. There are four of them: fire,
police, medical, and education. Each has its own buildings, its own
vehicles, and its own data layer.

## Fire

### Fire station
*Build your first fire station*

- *Dispatches fire engines along connected roads to fight fires.*
- A fire station is the first emergency building most cities build.
- *Two additional fire engines with their own dispatch and return
> trips.* — the annex that doubles your fleet.

### Fire training center
*Fire training center*

- Improves response time and capacity.
- *Fire science* — the research project that boosts fire response.

### Fire engine garage
*Fire engine garage*

- The annex that adds engines to an existing station.

### Fire drone hangar
*Fire drone hangar*

- An airborne alternative to fire engines.
- *A real station cell must be available before a patrol drone can
> respond.*

### Fire response
- *Fire at <address>* — the alert.
- *Fire engine on the way* — the in-game status.
- *Fires extinguished* — the daily counter.
- *Fires physically reached* — the alternate counter (some fires go
> out on their own).
- *Fighting fire* — the tooltip on a building on fire.
- *Treating on site* — when the fire is contained.
- *Calls not resolved in time* — when the response is too slow.

## Police

### Police station
*Build police station*

- *Two additional police cars. Detention capacity stays unchanged.* —
> the fleet annex.
- *Sixteen additional detention places. Does not add patrol cars.* —
> the detention annex.

### Patrol garage
*Patrol garage*

- Adds more patrol cars.

### Police drone hangar
*Police drone hangar*

- An airborne alternative to patrol cars.
- *A ground or air crew already owns this call* — the status when both
> arrive.

### Police response
- *Reported crime* — the daily counter.
- *Arrests completed* — the daily counter.
- *Detention occupancy* — the report line.
- *In custody* — the tooltip on a person.
- *Securing the incident* — the in-progress status.
- *Police have an open incident. Check the response route and detention
> capacity.* — the warning.

> *Gaming increases local crime pressure. Police access and capacity
> matter.* — the warning that casino and gaming districts raise crime.

## Medical

### Neighborhood clinic
*Build clinic*

- The basic medical building. *Coverage from clinics and hospitals.*
- *Hospital · 3,500 residents* — the rule of thumb for hospital
> coverage.

### Hospital / General hospital
*Build hospital*

- *Ambulances reach patients, stabilize them, and return to a reserved
> hospital bed.* — the workflow.
- *Two additional ambulances. Treatment places stay unchanged.* — the
> annex.

### Ambulance garage
*Ambulance garage*

- The annex that adds more ambulances.

### Care drone hangar
*Care drone hangar*

- An airborne alternative for medical response.

### Medical response
- *Medical call* — the alert.
- *Urgent medical call* — the high-priority variant.
- *Patient aboard* — the in-transit status.
- *Stabilizing patient* — the in-hospital status.
- *Case treated* — the closing status.
- *Cases treated · suspects admitted* — the closing status for police
> medical.
- *Patient transfer* — moving a patient between hospitals.
- *Care paused · transfer being arranged* — the status when a transfer
> is needed.
- *Deaths from untreated critical cases* — the cost of a slow
> response.
- *Unresolved or escaped cases* — the report line.

## Schools

### Primary school
*Build categories* — the build category is *Schools & learning*.

- *Every eligible student can reach a classroom. Keep room for the next
> generation.*

### Secondary school
- The next level of education.
- *SCHOOL BUS* — the school transport service.

### University
*Build a university*

- The third level. Unlocks research and the most advanced jobs.
- *Assign an operating university to this project.* — the requirement
> for the Horizon Institute.
- *Finish building this university first.* — the prerequisite warning.

### School bus
*School bus stop*

- The transport service for school children.
- *Two additional school buses. Classroom capacity stays unchanged.* —
> the annex.

### Schooling reports
- *Daily attendance* — the daily counter.
- *Recorded attendance, kept with your city.* — the line in the
> reports.
- *Months in this neighborhood* — the time spent in the school.
- *Lay the foundations for a city that keeps learning.* — the flavor
> line.

## The response map

The response data layer shows emergency coverage.

- **Green** — covered.
- **Orange** — under-served.
- **Red** — uncovered.

> *Reduce disaster damage and speed up fire response.* — a research
> project that improves the layer.

## Tips & common pitfalls

- **Coverage is not capacity.** A neighborhood can be covered but
  overwhelmed. Watch the *Calls not resolved in time* counter.
- **Roads are everything.** A station without a connected road can't
  dispatch. Keep emergency routes clear.
- **Pair services with growth.** As your city doubles in size, double
  the number of stations.
- **Schools need students.** A school without students is still a
  cost; consolidate when neighborhoods are small.
- **Drones are not a replacement.** A drone is faster, but a station
  has the bed, the detention cell, or the desk.

## Related pages

- [Weather and disasters](part-5-simulation/weather-and-disasters.md) —
  the events that test your emergency services.
- [Public transit](public-transit.md) — including school buses.
- [The data layers](part-6-tools/the-data-layers.md) — the response map.

---

### Screenshots to capture
- ![alt: The Public safety build menu. Cards: Fire station, Fire training center, Fire engine garage, Fire drone hangar, Police station, Patrol garage, Police drone hangar, Neighborhood clinic, Hospital, Ambulance garage, Care drone hangar. The Fire station card is selected.](../../assets/images/utilities/emergency-menu.png "The public safety build menu")
- ![alt: A fire in a downtown building. Smoke wisps rise from the second floor, a fire engine is on the way (visible in the response panel), and a small icon marks the building on fire. A "Fire at <address>" alert is at the top of the screen.](../../assets/images/utilities/emergency-fire.png "A fire in progress")
- ![alt: A police station with two patrol cars and a drone on the roof. A small "Reported crime: 3" indicator is visible, and the response map is on in the corner, showing green coverage across the downtown.](../../assets/images/utilities/emergency-police.png "A police station and its fleet")
- ![alt: A hospital with an ambulance garage annex. A helicopter pad is on the roof, and an ambulance is in the driveway. The medical response panel shows 12 cases treated today, 0 deaths.](../../assets/images/utilities/emergency-hospital.png "A hospital with an ambulance annex")
- ![alt: A primary school in a residential neighborhood. Children are visible on the playground, and a school bus is parked at the front. The "Daily attendance: 142" line is in the corner.](../../assets/images/utilities/emergency-school.png "A primary school with a school bus")
- ![alt: The response data layer active. The city is coloured from green (covered) to orange (under-served) to red (uncovered). A small legend reads "Average response, all services: 3.2 minutes."](../../assets/images/utilities/emergency-map.png "The response map")
