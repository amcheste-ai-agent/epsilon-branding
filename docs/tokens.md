# Epsilon — Design tokens

One warm graphite canvas, one honey amber accent, one Carolina blue for
secondary emphasis. One display face, one text face, one mono face.

## Palette

Warm graphite + honey amber + Carolina accent.

| Token | Role | Hex |
|---|---|---|
| Slate 900 | Canvas | `#161A26` |
| Slate 800 | Surface | `#1E2230` |
| Graphite | Avatar body | `#4A4F5C` |
| Honey | Eyes and ε mark | `#F5B84A` |
| Brass | Glyph accents | `#C99A45` |
| Carolina | Secondary (links, chart accents, jaw pinstripe) | `#4B9CD3` |

Use amber on warm graphite on slate. Carolina is secondary only — never
as a primary color.

## Type system

One display, one text, one mono.

| Role | Family | Weights |
|---|---|---|
| Display | [Fraunces](https://fonts.google.com/specimen/Fraunces) | 500 |
| Text | [Inter](https://fonts.google.com/specimen/Inter) | 400 / 500 / 600 |
| Mono | [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) | 400 / 500 |

### Display · Fraunces 500

For section heads, the README banner, and the avatar name card. Italic
when used for the ε mark itself. `letter-spacing: -0.015em`,
`line-height: 1.05` at display sizes.

### Text · Inter 400 / 500 / 600

For body copy, bios, and any medium-length prose. 400 for paragraph
text, 500 for emphasis, 600 for section labels.

### Mono · JetBrains Mono 400 / 500

For shell samples, file paths, commit hashes, and the CLI banner. When
used inline in prose, drop to 85% of surrounding text size.
