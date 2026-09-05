# Save and load

> *Your city, to keep.*

Lundby autosaves continuously. You don't have to do anything to keep
your city safe — but you can also save manually, export a `.lundby`
file, and load from any of the slots.

## Where to find it

- **City → Save & load**
- Or press **⌘S** (Ctrl+S on Windows).

> *Save & load* — the section.
> *SAVE & LOAD* — the section header.
> *Save city · ⌘S* — the action with the shortcut.

## The save slots

Lundby has the following save slots per origin:

- **Autosave** — *Autosave on* / *Autosave preparation* / *Autosaving…*
  / *AUTOSAVE* — the running autosave.
- **Recovery** — *RECOVERY SNAPSHOT* / *RECOVERY* / *Recovery* /
  *Recover from a disaster with 1,000 residents.* — a separate
  snapshot taken when something goes wrong.
- **Three manual slots** — *CITY SLOT 1* / *CITY SLOT 2* / *CITY
  SLOT 3* — your own saves.
- **Original** — *An original autosave is protected.* / *An
  original city-building game. All cities are stored on this
  device.* / *Your original save is protected.* / *Your original
  save, untouched.* / *Protected original data* / *Original base
  removed* / *Original retained in a protected copy · region saved*
  / *This copy is never replaced by automatic or manual saves.* —
  the protected original.

> *Manage saved cities* — the link.
> *View saved cities* / *Saved cities could not be read.* / *Saved
> cities* — the views.
> *Your previous cities will appear here. No export or manual save
> slot needed.* — the explanation.
> *No city saved here yet* — the empty slot state.

## Saving

### Manual save
1. Open the **Save & load** panel.
2. Pick a manual slot.
3. Click **Save**.
4. The city is saved.

> *Save city* / *Save city · ⌘S* / *Save encoder closed* — the save
> actions.
> *City save data* — the data.
> *City saved on this device* — the confirmation.
> *City save text copied* — the export confirmation.
> *The autosave could not be decompressed.* — the error.
> *The compressed city save is damaged.* — the error.
> *This city save encoding is not supported.* — the error.

### Autosave
- The game autosaves continuously.
- *Autosave on* / *Autosave preparation* / *Autosaving…* — the
  status.
- *AUTOSAVE* — the slot label.

> *An original autosave is protected.* — the warning that the
> autosave is part of the protected set.

### Recovery
- The game takes a recovery snapshot when something goes wrong.
- *RECOVERY* / *RECOVERY SNAPSHOT* — the labels.
- *Protect original and start fresh* / *Protect original and use
> recovery* — the actions.
- *Could not make the recovery save. Export your city first.* — the
> failure.
- *The city snapshot could not be prepared. Export a backup before
> reloading.* — the failure.
- *This saved city could not be loaded. Its backup has not been
> changed.* — the failure.

## Export and import

Lundby cities can be exported as `.lundby` files and imported back.
This is the only way to move a city between browsers, between
machines, or between ports.

### Export
1. Open the **Save & load** panel.
2. Click **Export city**.
3. The browser downloads a `.lundby` file.
4. Keep it anywhere you like.

> *Export city* / *Export copy* / *Export original autosave* / *Export
> protected original* / *Export this region* / *Export unavailable*
> / *Export city* — the actions.
> *Download city file* / *Download original data* / *Download* — the
> download actions.
> *Your city, to keep.* — the flavor line.
> *Keep a copy of your city.* — the prompt.
> *Could not make the recovery save. Export your city first.* — the
> failure.

### Import
1. Open the **Save & load** panel.
2. Click **Import city** or **Paste a backup**.
3. Pick the `.lundby` file or paste the save text.
4. Confirm.

> *Import city* / *Paste a backup* / *Paste city save data* / *Paste
> the full save text here* — the import actions.
> *Could not read that file.* — the failure.
> *Could not read this backup.* — the failure.
> *This file is not a readable Lundby save.* — the failure.
> *This is not a supported Lundby city.* — the failure.
> *That file is too large.* — the failure.
> *This save is too large.* — the failure.
> *This save could not be loaded.* / *This save could not be read.* —
> the failures.
> *This city is no longer available.* / *This saved city is no
> longer available.* — the variant.
> *This saved city could not be read.* — the variant.
> *The city snapshot could not be prepared. Export a backup before
> reloading.* — the recovery hint.

### Copy and paste
- *Copy save text* — copies the save text to the clipboard.
- *Hide save text* / *Show save text* — toggles the save text
> display.
- *Select and copy the full text. Use "Paste a backup" in Save &
> load to restore it.* — the prompt.
- *Select the save text and copy it with your keyboard.* — the
> variant.
- *City save text copied* — the confirmation.
- *Restore pasted city* / *Cancel pasted backup* — the actions.

## The save protection system

> *Save protection* / *SAVE PROTECTION* — the section.
> *Saving is paused. Review save protection or export a backup.* —
> the warning.
> *Saving is paused. Review save protection.* — the variant.
> *Saves protected · review* — the status.
> *Review save protection* — the action.
> *Remove saved copy* / *Remove this saved copy of* / *Remove this
> copy* — the actions.
> *This copy could not be removed. Check save protection and try
> again.* — the failure.
> *The city government record is damaged.* / *The save contains
> invalid city data.* / *The save is incomplete.* / *The save
> contains an invalid calendar date.* / *The save contains an
> invalid disaster record.* / *The save contains damaged history
> or district records.* / *The save contains invalid budget
> settings.* / *The save contains invalid districts.* / *The save
> contains invalid household tax rates.* / *The save contains
> invalid policy or debt data.* / *The save contains invalid
> regional or progression records.* / *The save contains invalid
> simulation settings.* / *The save could not be simulated safely.*
> — the save errors.

### Save protection features
- **Protected original** — the original autosave is never replaced
  by a manual save.
- **Three manual slots** — *CITY SLOT 1 / 2 / 3* — your own saves.
- **Recovery snapshot** — taken automatically on errors.
- **Region backup** — *Current region backup* / *Emergency region
> backup* — the regional saves.

> *This copy is never replaced by automatic or manual saves.* — the
> protected state.

## Loading

> *Load this city? Your current city will be saved automatically
> first.* — the confirmation.
> *Open city* / *Open city menu* / *Open and staff the corporate
> headquarters* — the open actions.
> *Continue city* — the action.
> *Replace this saved city with your current city?* — the
> confirmation.
> *A newer save was found.* — the warning.

## What's where

- **Saves are in `localStorage`.** They live in your browser, on the
  origin you served the game from.
- **Saves are per-browser and per-port.** A different port means a
  fresh city list.
- **Clearing site data wipes your cities.** Always export first.

> *An original city-building game. All cities are stored on this
> device.*
> *The browser is not allowing access to saved cities.* — the
> failure.
> *This browser is not allowing access to local saves.* — the
> variant.

## Tips & common pitfalls

- **Export often.** A `.lundby` file is the only thing that survives
  a browser reset.
- **Don't trust the autosave alone.** The autosave can fail; a
  manual export is your real backup.
- **Saves are tied to the origin.** A `localhost:9090` save is not
  the same as a `localhost:8080` save.
- **Recovery is not a substitute for export.** A recovery snapshot
  is a one-shot — if the next save fails, you've lost it.

## Related pages

- [Save protection](save-protection.md) — the protection system.
- [Offline play and updates](offline-play-and-updates.md) — the
  offline flow.
- [Photo mode](photo-mode.md) — exporting a photograph, not a city.

---

### Screenshots to capture
- ![alt: The Save & load panel. A list of save slots: Autosave, Recovery, City Slot 1, City Slot 2, City Slot 3. Each slot shows the city name, the population, the save date, and a small thumbnail. The autosave is highlighted. "Export" and "Import" buttons are at the bottom.](../../assets/images/save/save-panel.png "The save and load panel")
- ![alt: The export dialog. A small window with a "Download city file" button. A note reads "Your city, to keep." A small preview of the .lundby file name is visible.](../../assets/images/save/save-export.png "The export dialog")
- ![alt: The import dialog. A small window with a "Paste the full save text here" text area. A "Restore pasted city" button is at the bottom. A "Cancel pasted backup" button is next to it.](../../assets/images/save/save-import.png "The import dialog")
- ![alt: The save protection panel. A list of saved copies with toggles: Protected original, Autosave, Recovery, City Slot 1, City Slot 2, City Slot 3. A "Saving is paused. Review save protection or export a backup." warning is at the top.](../../assets/images/save/save-protection.png "The save protection panel")
