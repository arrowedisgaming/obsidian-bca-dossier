# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

- Callout titles now vertically center the icon glyph against the title
  text across all callout types (`classified`, `memo`, `stamp`, `redacted`).
- Removed the underline rules on H1 and H2. Both `border-bottom` and
  `text-decoration` paint per visual line when the inline heading span
  wraps in Live Preview, leading to underlines striking through every
  line of a wrapped heading. The oxblood + Big Shoulders / Oswald
  uppercase treatment carries the visual weight on its own.
- Coffee stains redrawn as organic, irregular blobs using SVG turbulence +
  displacement maps. Outer meniscus stroke is thicker and varies in
  opacity, satellite drips added outside each ring.

### Added

- Four scattered viewport-fixed liquid stains (top-right partial arc,
  bottom-left drip splotch, mid-right secondary ring, top-left accent
  splash) so the page surface feels marked-up beyond just the sidebars.

## [0.1.0] - 2026-04-22

### Added

- Initial release of the BCA Dossier Obsidian CSS snippet (`bca-dossier.css`).
- Light and dark dossier themes sharing a paper / ink / oxblood / teal / amber palette.
- Six imported Google Fonts: Special Elite, Courier Prime, Big Shoulders Display, Oswald, Share Tech Mono, Atkinson Hyperlegible.
- Four custom callout types: `classified`, `memo`, `stamp`, `redacted`, each with stamped borders and in-universe icons.
- Interactive redaction bars via `==text==` that reveal their contents on hover or tap.
- Dossier-styled tables with uppercase stencil headers and striped rows.
- Perforated horizontal-rule dividers.
- Paper-grain texture overlay and sidebar decorations (coffee rings, classified stamp).
- `BCA Dossier Style Showcase.md` — a living reference document exercising every styled element.
- `README.md` mirroring the showcase for GitHub viewers.

[Unreleased]: https://github.com/arrowedisgaming/obsidian-bca-dossier/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/arrowedisgaming/obsidian-bca-dossier/releases/tag/v0.1.0
