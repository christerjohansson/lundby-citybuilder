# Contributing

> *Your city starts here.*

The Mayor's Handbook lives in `docs/`. It's a GitBook, with one
Markdown file per page and a `SUMMARY.md` that defines the table of
contents.

## File layout

```
docs/
├── README.md                   The landing page
├── SUMMARY.md                  The GitBook table of contents
├── part-1-welcome/             Part I — Welcome, Mayor
├── part-2-build/               Part II — Build the City
├── part-3-utilities/           Part III — Utilities & Services
├── part-4-economy/             Part IV — Economy & Civics
├── part-5-simulation/          Part V — Simulation
├── part-6-tools/               Part VI — Tools & Interface
├── part-7-save/                Part VII — Save, Load & Play
├── appendix-developers/        Appendix A — For Developers
└── assets/images/              Image assets for the book
```

## Adding a new page

1. **Pick the right part.** The seven parts cover the game's
   surface; the appendix is for developers. If your topic doesn't
   fit, propose a new part.
2. **Create the file.** Use a kebab-case name. Put it in the right
   part folder.
3. **Use the page template.** Each page has the same shape:
   - `# Title`
   - `> Flavor quote`
   - `## What it is`
   - `## How to use it`
   - `## Key controls / shortcuts`
   - `## Tips & common pitfalls`
   - `## Related pages`
   - `### Screenshots to capture`
4. **Add the page to `SUMMARY.md`.** In the right part, add a
   bullet: `* [Title](part-N-name/file.md)`.
5. **Add image placeholders.** For each screenshot, use the
   standard GitBook syntax with detailed alt text:
   `![alt: Description of what the screenshot should show.](path "Caption")`.
6. **Cross-link.** Add `## Related pages` with links to other
   pages in the book.
7. **Commit on a topic branch.** Open a pull request.

## Editing a page

1. **Open the file** in `docs/`.
2. **Edit** the Markdown. Keep the page template shape.
3. **If you change the section structure,** update `SUMMARY.md` if
   needed.
4. **If you add a new screenshot placeholder,** use a descriptive
   filename.
5. **Commit on a topic branch.** Open a pull request.

## Style guide

- **Voice:** in-game, friendly, "Mayor" voice. Use the in-game
  flavor lines where they exist.
- **Length:** aim for 200–500 words per page. Some pages need more.
- **Lists:** use bullet lists for short items; use numbered lists
  for steps.
- **Code:** use code formatting for keyboard keys (**R**, **Esc**,
  **⌘S**), file names (`index.html`), and class names.
- **Bold:** use bold for UI elements (the **Build** menu, the
  **Save & load** panel).
- **Italics:** use italics for in-game flavor quotes and for the
  names of buildings or scenarios.
- **Headings:** start at `##` (the page title is `#`).
- **Screenshots:** always include a detailed alt text. The alt
  text is a full sentence describing what the screenshot must
  show, including UI state, what is selected, and the visible HUD
  elements.

## Screenshot pass

Each page ends with a `### Screenshots to capture` section. When
the screenshot pass runs:

1. Load the game.
2. Build or load the city to the state described by the alt text.
3. Frame the shot to match the alt text.
4. Capture and save with the filename suggested by the
   placeholder.

> See the [README.md](../../README.md) for the existing
> screenshots in the `screenshots/` folder.

## The GitBook config

The book uses GitBook's standard layout. The `.gitbook.yaml` at the
repo root tells GitBook where the book lives:

```yaml
root: ./docs
```

If you need to add plugins, structure overrides, or translations,
add them to `.gitbook.yaml`.

## Running the book locally

GitBook CLI is the easiest way to preview the book locally:

```bash
npm install -g gitbook-cli
gitbook install
gitbook serve
```

Or use the GitBook.com editor to edit the book in the browser.

## Related pages

- [Project layout](project-layout.md) — the file tree.
- [Tech notes](tech-notes.md) — the bundle.
- [The string table](the-string-table.md) — the source for the
  handbook content.

---

### Screenshots to capture
- ![alt: A GitBook preview of the handbook in a browser. The sidebar shows the table of contents with the seven parts and the appendix. The main panel shows a chapter with the Mayor's voice. The screenshots are still placeholders.](../../assets/images/appendix/gitbook-preview.png "A GitBook preview of the handbook")
