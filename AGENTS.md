# The Golden Ruin Assistant Notes

This repository is the CampaignRepo content repo for **The Golden Ruin**.

When Patric asks to "build a page", "make a page", "add this to Golden Ruin", or gives a brief campaign note, create or update CampaignRepo Markdown pages in this repo unless he points somewhere else.

## Repo Conventions

- Campaign path: `C:\Users\patricthomas\The-Golden-Ruin`
- GitHub repo: `https://github.com/avorial/The-Golden-Ruin`
- Campaign config: `wiki/campaign.yaml`
- Pages: `wiki/pages/<Slug>.md`
- Media: `wiki/media`
- Templates: `wiki/templates/The King in Yellow RPG`
- Manifest/search files under `.campaignrepo` and `wiki/search` are generated snapshots; update them only when the task explicitly calls for it or when a CampaignRepo script requires it.

## Page Rules

- Preserve YAML frontmatter on every page.
- Use CampaignRepo wiki links: `[[Page Name]]` or `[[Page Name|label]]`.
- Use `:::gm` blocks for secrets, hidden causes, GM-only motives, and unrevealed truths.
- New AI-created pages should usually land with `approvalStatus: unapproved`, `visibility: gm`, and `knownToPlayers: false` unless Patric says they are player-facing.
- If Patric asks for a player handout, public-facing lore, or a page players should see, use `visibility: players`, `knownToPlayers: true`, and set `approvalStatus: approved` only when he clearly wants it published now.
- Pick the closest existing category from `wiki/campaign.yaml`: `character`, `npc`, `organization`, `species`, `location`, `item`, `spell`, `religion`, `vehicle`, `event`, `lore`, or `game`.
- Keep page filenames slug-like and stable. Existing pages may use title case, so prefer `House-of-the-North-Star.md` style for new title pages unless the repo already has a matching slug.

## Tone

The Golden Ruin uses **The King in Yellow RPG** as its game type. Favor uncanny elegance, decadent decay, theatrical dread, unreliable memory, symbols that feel too deliberate, and mundane details that become ominous under attention. Make content useful at the table: clear hooks, concrete locations, named NPCs, relationship links, visible clues, and GM-only truths.

Avoid generic cosmic-horror filler. Tie new pages to existing pages whenever possible, especially `[[House of the North Star]]`.

## Default New Page Shape

```markdown
---
category: lore
type: lore
name: Page Name
summary: One sentence table-use summary.
tags:
  - lore
visibility: gm
approvalStatus: unapproved
knownToPlayers: false
keyLinks: []
aliases: []
lastEditedBy: Codex
---

# Page Name

## Overview

Concrete, campaign-ready prose.

## Table Use

- A clue, scene, choice, or pressure point.

## Links

- [[House of the North Star]]

:::gm
Hidden truth, motive, cost, or reveal.
:::
```

## Workflow

1. Read nearby existing pages before adding new continuity.
2. Create or update the smallest useful set of Markdown files.
3. Run a quick `git status --short` and inspect the diff before reporting back.
4. Do not commit or push unless Patric explicitly asks.
