# DOSSIER - BCA Styling Snippet for Obsidian

> **TRANSMISSION INTERCEPTED · CLASSIFIED · EYES ONLY**
>
> An Obsidian CSS snippet that dresses your vault in the aesthetic of DNGN Club's [Bureau of Chronological Affairs](https://dngnclub.itch.io/bureau-of-chronological-affairs): redaction bars, stamped callouts, perforated dividers, and paper-grain texture. Turn any note into a temporal agent's field dossier.

---

## Overview

`bca-dossier.css` is a single-file Obsidian snippet that overhauls the look of your vault to resemble a 20th-century classified case file. Drop it in, toggle it on, and every note you open inherits:

- Warm paper / oxblood / teal / amber palette, with a matching dark theme
- Stamped, bordered callouts in four in-universe varieties
- Interactive redaction bars that reveal their contents on hover
- Dossier-styled tables with uppercase stencil headers
- Perforated form-style horizontal rules
- A subtle paper-grain overlay and coffee-ring sidebar decorations

It's designed for TTRPG notes, worldbuilding, investigative fiction, and anyone whose notes feel like they should have been stamped `TOP SECRET` in red ink and then immediately forgotten in a filing cabinet.

---

## Installation

1. Download [`bca-dossier.css`](bca-dossier.css) (use the **Raw** button and save the file).
2. Move it into your vault's snippets folder:
   ```
   <your-vault>/.obsidian/snippets/bca-dossier.css
   ```
3. In Obsidian, open **Settings → Appearance → CSS snippets** and toggle **bca-dossier** on.
4. (Optional) Open [`BCA Dossier Style Showcase.md`](BCA%20Dossier%20Style%20Showcase.md) inside your vault to see every styled element render live.

---

### Fonts

The snippet pulls six Google Fonts at load time:

| Role | Family |
|---|---|
| Body | Special Elite |
| Display / bold | Oswald |
| H1 | Big Shoulders Display |
| Italic | Atkinson Hyperlegible |
| Code | Share Tech Mono |
| Monospace alt | Courier Prime |

If you need the vault to work offline, self-host these fonts and swap the `@import` line at the top of the CSS.

---

## Showcase

The file [`BCA Dossier Style Showcase.md`](BCA%20Dossier%20Style%20Showcase.md) is a living reference that exercises every styled element: heading hierarchy, body text, links, redaction, all four callouts, code blocks, tables, lists, tags, and long-form typography. Open it inside Obsidian with the snippet enabled for a full visual test.

---

## Changelog

See [`CHANGELOG.md`](CHANGELOG.md) for version history.

## License

[MIT](LICENSE)