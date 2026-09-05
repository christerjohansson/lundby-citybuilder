# Jobs and employment

> *A good job is worth keeping.*

Jobs are how the city sustains itself. Every workplace hires from the
local pool, every household needs a job, and the match between them is
the daily employment simulation.

## The three job types

> *Entry / trained / specialist jobs* — the three job types.

- **Entry** — basic jobs, no training required.
- **Trained** — requires secondary education.
- **Specialist** — requires higher education.

> *Trained roles* / *Professional roles* — the workforce categories.
> *General roles* / *Trained, including professionals* — the report
> labels.

## How residents find jobs

> *How residents choose a job* — the in-game explainer.

The simulation runs every city day:

1. A household with working-age members looks for a job.
2. The job has to be reachable — by walking, cycling, transit, or
   driving.
3. The household picks the best match.
4. The worker commutes daily and earns a wage.

> *From home to work* — the journey type.
> *No available walking, cycling, road, or transit connection to this
> workplace* — the failure case.
> *Try another employer, home or change type.* — the suggestion.

### Commute failures
- *No available walking, cycling, road, or transit connection to this
> workplace*
- *No route home* / *No route*
- *The commute needs a continuous connection*
- *This commute has reached its transfer limit*
- *No affordable route home from the current stop or street*
- *Waiting at home for a work connection* — the status.

## Workplace reports

- *Jobs & workplaces* — the management menu section.
- *Workplace* / *Workplace name or coordinates* — the search field.
- *LOCAL EMPLOYER* / *REGIONAL EMPLOYER* — the workplace type label.
- *Workplace assignments* — the assignments list.
- *Workplace reports will be ready after the city's next report.* —
> the delay note.
- *Find a workplace or home* — the search.

> *Available workers* / *Available workforce* / *Working / positions*
> — the workforce reports.
> *Skilled vacancies* — the open positions.
> *Open positions* — the report.

## Employment conditions

> *Employment condition* — the report.
> *Employed residents* / *Not at work* / *Not currently at work* — the
> daily state.
> *At work* / *Heading to work* — the in-game status.
> *Household work* / *HOUSEHOLD WORK* — the section.
> *The people behind the skyline* — the flavor line.

### Career progression
> *Workers promoted* — the daily event.
> *Open for hiring* / *NOT HIRING* — the workplace status.
> *Hiring review due* — the periodic review.

## How the commute works

> *The commute needs a continuous connection* — the rule.
> *Average connected commute* — the report.
> *The walking route is broken; restore a local street* — the warning.
> *The walking connection is missing; restore a local street* — the
> variant.
> *Restore a continuous route from the workers' current location* —
> the recovery hint.

### By mode
- **Walk** — *Walk to work* / *Walk from home* / *Walk from the tower
> entrance* / *Walk to the tower entrance* — the walk labels.
- **Cycle** — *Connected cycling* — the cycling mode.
- **Drive** — *Drive to parking* / *Walk from parking* — the driving
> mode.
- **Transit** — *By metro* / *By streetcar* / *By maglev* / *By
> commuter rail* / *By ferry* — the transit modes.

### Transfers
> *With transfers* / *One-way journey* / *One-way time* — the journey
> properties.
> *This journey has exhausted its transfer allowance* — the failure.
> *The walking route is broken; restore a local street* — the
> transit-side failure.
> *The connecting service's route or stops changed* — the route
> change.
> *The vehicle's route is broken; passengers and cargo remain
> aboard* — the in-transit failure.

## Employment reports

The **EMPLOYMENT VIEWS** panel shows:

- *Population toward next council slot* — the population summary.
- *Skilled vacancies* — the open roles.
- *Open positions* — the count.
- *All job changes* — the daily log.
- *Find job moves* — the search.
- *Job move type* — the filter.
- *Job opportunities and moves* — the panel.
- *Next job moves* / *Previous job moves* — the paging.
- *Next employment records* / *Previous employment records* — the
> historical view.
- *Employment report* — the per-city report.
- *Employment connections* — the commute view.

> *A workplace assignment is damaged.* — the error.
> *The employment history assigns more workers than its capacity.* —
> the error.
> *The employment history is invalid.* — the error.
> *The employment opportunity history is invalid.* — the error.
> *The employment move totals are damaged.* — the error.
> *The compact employment history is invalid.* — the error.
> *A saved employment move is damaged.* — the error.

## Workforce education

> *Connected workforce education* — the high-skill workforce metric.
> *Learning beyond the classroom* — the flavor line.
> *Learning opens new roles. Better connections bring work closer to
> home.* — the lesson.
> *Bright minds* / *Lay the foundations for a city that keeps
> learning.* — the education flavor lines.

## Tips & common pitfalls

- **Match jobs to education.** Trained jobs need trained workers.
- **Commute time matters.** A 30-minute commute is a different city
  than a 5-minute commute.
- **Transit unlocks jobs.** A bus line can move a worker from a
  residential block to a downtown office in minutes.
- **Workplace size matters.** A large workplace has more jobs; a
  small one has fewer.
- **Job moves are the churn.** *All job changes* is the daily log of
  moves.

## Related pages

- [Population and households](population-and-households.md) — the
  workers.
- [Public transit](part-3-utilities/public-transit.md) — the commute
  network.
- [Schools & learning](part-3-utilities/emergency-services.md#schools) —
  the education pipeline.

---

### Screenshots to capture
- ![alt: The employment report. A summary: 8,400 employed residents, 1,200 seeking work, 320 skilled vacancies. Below, a bar chart of job types: 4,200 entry, 2,800 trained, 1,400 specialist. A second chart shows the average commute time by mode: walk 12 min, cycle 18 min, drive 24 min, transit 31 min.](../../assets/images/simulation/employment-report.png "The employment report")
- ![alt: The employment connections map. Roads are coloured by commute volume. The downtown office district glows orange (high inbound commute); a residential block on the edge glows green (low outbound commute). A small legend reads "Average connected commute."](../../assets/images/simulation/employment-map.png "The employment connections map")
- ![alt: A workplace in the commercial district. A medium-sized office building with a "LOCAL EMPLOYER" label. A few workers are visible entering. A "Hiring review due" badge is on the corner.](../../assets/images/simulation/employment-workplace.png "A workplace in the commercial district")
- ![alt: The job moves log for the day. A list of moves: a worker promoted from entry to trained at a factory, a household moved closer to a new job, a worker retired. A "Find job moves" search bar is at the top.](../../assets/images/simulation/employment-moves.png "The job moves log")
