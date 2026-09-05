# Save protection

> *Saving is paused. Review save protection.*

Lundby's save system is designed to never lose your city by accident.
The **save protection** panel is where you review the rules that
protect your saves.

## Where to find it

- **City → Save & load → Save protection**

> *Save protection* / *SAVE PROTECTION* — the section.
> *Review save protection* — the action.
> *Saving is paused. Review save protection or export a backup.* —
> the warning.
> *Saving is paused. Review save protection.* — the variant.

## What's protected

### The original autosave
- The very first autosave of a city is **protected** — it cannot be
  replaced by a manual save.
- *An original autosave is protected.* — the notice.
- *Your original save is protected.* — the variant.
- *Your original save, untouched.* — the reassurance.
- *Protected original data* — the data label.
- *This copy is never replaced by automatic or manual saves.* — the
  rule.

> *Original retained in a protected copy · region saved* — the
> confirmation when the original is kept.

### The recovery snapshot
- A recovery snapshot is taken when the simulation encounters an
  error.
- *RECOVERY SNAPSHOT* / *RECOVERY* — the labels.
- *Protect original and start fresh* / *Protect original and use
> recovery* — the actions.
- *Could not make the recovery save. Export your city first.* — the
> failure.

### The three manual slots
- *CITY SLOT 1* / *CITY SLOT 2* / *CITY SLOT 3* — your own saves.
- Each can be replaced at will.
- Each can be exported or deleted.

> *Remove saved copy* / *Remove this saved copy of* / *Remove this
> copy* — the actions.
> *This copy could not be removed. Check save protection and try
> again.* — the failure.

## How save protection works

When you save, the game follows these rules:

1. **Protected copies are never replaced.** The original autosave
   stays.
2. **Recovery snapshots are one-shot.** A new recovery overwrites
   the old one.
3. **Manual slots are fair game.** Save into any of the three slots
   at any time.
4. **A damaged save is not deleted.** It's flagged with an error
   message.

> *Saves protected · review* — the all-clear.

## When to use save protection

- **When you're not sure if a save is good.** The recovery snapshot
  is a safety net.
- **When you want to experiment.** Save into a manual slot, then
  experiment. If the experiment fails, reload.
- **When you're handing the city off.** Export to `.lundby` and
  keep the file.

## Save errors

> *The save contains invalid city data.* / *The save is incomplete.*
> / *The save contains an invalid calendar date.* / *The save
> contains an invalid disaster record.* / *The save contains
> damaged history or district records.* / *The save contains
> invalid budget settings.* / *The save contains invalid
> districts.* / *The save contains invalid household tax rates.* /
> *The save contains invalid policy or debt data.* / *The save
> contains invalid regional or progression records.* / *The save
> contains invalid simulation settings.* / *The save could not be
> simulated safely.* — the save errors.

If you see a save error, the save is damaged. The game will offer
to load the most recent good save.

> *The city snapshot could not be prepared. Export a backup before
> reloading.* — the warning.

## Region backups

> *Current region backup* / *Emergency region backup* — the regional
> backups.
> *Reload latest saved region* / *Reload saved region* — the
> recovery actions.
> *This tab can safely save your region.* — the safety check.
> *Checking that this tab can safely write the region's saves.* —
> the check.
> *This region is open in another tab.* — the multi-tab warning.
> *The region contains an invalid city plot.* — the error.

## Tips & common pitfalls

- **The recovery snapshot is a one-shot.** If a second error happens
  before you've restored, the recovery is gone.
- **The original autosave is sacred.** It cannot be replaced, but
  it can be exported.
- **Save protection is per-city.** Each city in the region has its
  own save set.

## Related pages

- [Save and load](save-and-load.md) — the full save workflow.
- [Offline play and updates](offline-play-and-updates.md) — the
  offline flow.
- [Regional cities](part-5-simulation/regional-cities.md) — the
  region's saves.

---

### Screenshots to capture
- ![alt: The save protection panel. A list of save slots with status indicators: Protected original (locked icon), Autosave (regular icon), Recovery (warning icon), City Slot 1, 2, 3 (regular icons). A "Saving is paused. Review save protection or export a backup." warning is at the top.](../../assets/images/save/protection-panel.png "The save protection panel")
- ![alt: A recovery snapshot dialog. A confirmation message: "We’ll save the original and offer a recovery slot." A "Continue" button is at the bottom.](../../assets/images/save/protection-recovery.png "A recovery snapshot dialog")
