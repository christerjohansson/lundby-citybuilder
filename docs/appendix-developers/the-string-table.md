# The string table

> *Mayor's handbook*

Lundby's bundle is one minified line of JavaScript. It's not human-
readable as shipped, but a de-minified copy lives in
[`readable/index.js`](../../readable/index.js) for study.

The de-minified copy reveals a large **string table** — every
player-facing piece of text in the game, in one place. This
handbook was extracted from that table.

## What the string table contains

The string table is a long list of double-quoted strings. Most of
the meaningful text in the game is in there:

- **UI labels** — *Zoning* / *Build* / *Save* / *Load* / *Settings*.
- **Panel headers** — *CITY PULSE* / *CITY COUNCIL* / *CITY TRANSIT*
  / *CITY LOGISTICS* / *CITY FUNDS* / *CITY CONTROL NETWORK* / *CITY
  TRAMWORKS* / *MANUFACTURED CITY SERVICES* / *CITY DESK*.
- **Tooltip text** — *Click a building to inspect. Drag to pan;
  right-drag to orbit.*
- **Error messages** — *A commuter train is unavailable; the group
  stays on the platform* / *A transit line is damaged.*
- **Flavor lines** — *A breath of fresh air* / *A city in motion.* /
  *A living, breathing city* / *A moving storm leaves a narrow
  trail of damage.*
- **Scenario intros** — *A mountain valley above a clear lake. Plan
  around slopes and protect the forest.* / *A winding river divides
  fertile banks. Bridges and transit connect both sides.* / *A
  waterfront destination. Must be close to the shore.*
- **Milestone text** — *A city finding its rhythm* / *A city of
  every generation* / *A city that takes care.* / *A city with a
  life of its own.*
- **The "Mayor's handbook"** — the literal string *Mayor's handbook*
  and *THE MAYOR'S HANDBOOK* live in the bundle. This book is the
  realisation of that in-game reference.

> *Mayor's handbook* / *THE MAYOR'S HANDBOOK* — the in-game
> reference.

## How the string table was extracted

The extraction is straightforward:

1. Read the de-minified file as text.
2. Use a regular expression to find all double-quoted strings of 2
   or more characters.
3. Filter to those that begin with an uppercase letter or a
   digit (drop the noise — JavaScript syntax, SVG paths, Three.js
   error messages).
4. Deduplicate.
5. Sort and review.

The result is a few thousand strings. The bulk of them are
player-facing text; the rest are SVG path data and Three.js error
messages that slipped through the filter.

## What the string table is for

The string table is the **single source of truth** for the
handbook. If a feature is in the game, it's in the string table,
and it should be in the book.

If you find a feature in the game that isn't in the book, please
open a pull request that adds a page for it.

> See [Contributing](contributing.md).

## What the string table isn't for

- **It's not the game logic.** The actual behaviour is in the
  minified code; the strings are just the text the game shows.
- **It's not a complete API.** Some in-game text is computed at
  runtime (numbers, dates, names) and isn't in the string table.
- **It's not localised.** The string table is English-only. Other
  languages, if they exist, live elsewhere.

## The Three.js error messages

The string table also contains a long list of Three.js error
messages — *THREE.WebGLProgram: Shader Error* / *THREE.WebGLRenderer:
Context Lost.* / etc. These are developer-facing diagnostics that
ship with the bundled Three.js. The book doesn't document them; if
you see one, it's a bug report.

> *WARNING: Multiple instances of Three.js being imported.* — the
> most common developer warning.

## SVG path data

The string table also contains a lot of SVG path data — the icon
glyphs that ship with the bundle. These are not in the book; if
you see one, it's an icon path.

## Related pages

- [Project layout](project-layout.md) — the file tree.
- [Tech notes](tech-notes.md) — the bundle structure.
- [Contributing](contributing.md) — how to add a page.

---

### Screenshots to capture
- ![alt: A text editor showing a small slice of the string table. The strings are sorted alphabetically. Visible: "A breath of fresh air", "A building record is damaged.", "A business development record is damaged.", "A call for public safety", "A city can operate up to 16 transit lines.", "A city event attendance or date record is invalid.", "A city event venue is double-booked.", "A city finding its rhythm", "A city hall for a city with ambition."](../../assets/images/appendix/strings-slice.png "A slice of the string table")
