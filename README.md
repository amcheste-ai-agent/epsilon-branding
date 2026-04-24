<p align="center">
  <img src="avatar/epsilon-avatar-460.png" alt="Epsilon avatar" width="230" />
</p>

<h1 align="center"><em>ε</em> Epsilon</h1>

<p align="center"><em>small, but essential.</em></p>

---

## What Epsilon is

Epsilon is the visual identity for [`amcheste-ai-agent`](https://github.com/amcheste-ai-agent),
a personal AI coding agent built on Claude Code. The agent commits code,
opens pull requests, and leaves every merge decision to a human reviewer.
This repo is the canonical source of truth for Epsilon's mark, palette,
type, profile copy, and social assets — everything that makes Epsilon
recognizable at a glance.

The name comes from the ε in analysis — the arbitrarily small positive
quantity that makes a proof work. Small, precise, essential. That's the job.

## Who owns this

| | |
|---|---|
| **Bot account** | [`amcheste-ai-agent`](https://github.com/amcheste-ai-agent) (display name: Epsilon) |
| **Human reviewer** | [`@amcheste`](https://github.com/amcheste) |
| **Design rationale** | [engineering-handbook / claude-bot-account](https://github.com/amcheste/engineering-handbook/blob/develop/docs/design/claude-bot-account.md) |
| **Agent implementation** | [amcheste-ai-agent/epsilon-agent](https://github.com/amcheste-ai-agent/epsilon-agent) |

## Using the ε mark

- Lowercase italic **Fraunces ε** in **honey amber** (`#F5B84A`).
- Appears as the avatar's forehead mark, as the bullet for taglines, and
  inline wherever we reference the identity by symbol alone.
- One glyph, repeated everywhere. Don't invent variants.

Full do/don't rules: **[`docs/usage.md`](docs/usage.md)**.
Colors, fonts, and sizes: **[`docs/tokens.md`](docs/tokens.md)**.

## Repository layout

```
avatar/   circle-crop avatars at 80, 200, 460, 1024 px + source SVG
social/   1280 × 640 social preview card (PNG) + HTML source
cli/      splash banner for the CLI wrapper (PNG) + HTML source
kit/      full interactive branding kit (HTML)
docs/     usage rules and design tokens (Markdown)
```

## Licensing

Art is **CC BY 4.0**. Code and documentation are **MIT**. See [`LICENSE`](LICENSE)
for the full text of both. Attribution required for reuse.

## Not a shared logo

Epsilon is one person's personal agent identity. If you're adopting the
bot-account pattern yourself, create your own mark — don't reuse Epsilon's
to represent a different agent. The setup guide at
[`amcheste-ai-agent/epsilon-agent`](https://github.com/amcheste-ai-agent/epsilon-agent)
walks through building a fully independent instance.
