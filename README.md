# The Golden Ruin

An investigative horror campaign set amid the salons, studios, and theatres of Belle Epoque Paris. The House of the North Star brings artists and wealthy expatriates into a web of patrons, old associations, unsettling works of art, and memories that no longer agree with reality.

**Game system:** The King in Yellow RPG\
**Campaign manager:** [CampaignRepo](https://github.com/avorial/CampaignRepo)

## Game System

The Yellow King Roleplaying Game is an investigative horror game inspired by Robert W. Chambers. Its stories connect unsettling art, unreliable reality, and lives across different settings and timelines. Investigators follow clues while confronting the physical and psychological consequences of contact with the Yellow King's influence. [Pelgrane Press's Yellow King overview](https://pelgranepress.com/product/the-yellow-king-rpg/).

The campaign configuration names this system `The King in Yellow RPG`; the publisher's title is `The Yellow King Roleplaying Game`.

The table's chosen edition and house rules govern play. This repository records campaign material and references; it does not replace the game's rulebooks.

## What CampaignRepo Does

CampaignRepo turns these files into a browser-based campaign workspace. It links characters, NPCs, factions, places, items, and session notes into a searchable wiki, with maps, relationship graphs, calendars, quests, and media tools available as the campaign develops.

Owners and GMs can keep private material alongside approved player-facing pages, review imported or AI-assisted drafts, and publish selected content through a player portal or public campaign site. The underlying Markdown, YAML, JSON, and media files remain readable without CampaignRepo.

## Start Reading

- [House of the North Star](wiki/pages/House-of-the-North-Star.md)
- [Session One Notes](wiki/pages/Session-One-Notes.md)
- [Session Two Notes](wiki/pages/Session-Two-Notes.md)
- [All wiki pages](wiki/pages/)
- [Campaign configuration](wiki/campaign.yaml)

## Repository Structure

| Path | Contents |
| --- | --- |
| `wiki/pages/` | Wiki articles, characters, lore, and published session reports |
| `wiki/media/` | Images, maps, handouts, and other media |
| `wiki/templates/` | Game-specific page and character templates |
| `wiki/imports/characters/` | Preserved character import sources, when used |
| `wiki/sessions/` | Structured session preparation and notes, when used |
| `wiki/quests/` | Quest records, objectives, and clocks, when used |
| `wiki/maps/` | Map records and linked pins, when used |
| `wiki/campaign.yaml` | Campaign name, game system, categories, and settings |
| `.campaignrepo/index.json` | Generated navigation manifest |
| `wiki/search/index.json` | Generated portable search snapshot |

Some folders are created when their tools are first used. Pages and their frontmatter are the source of truth; generated indexes can be rebuilt.

## Editing and Sharing

- Preserve each page's YAML frontmatter.
- Use `[[Page Name]]` or `[[Page Name|label]]` for wiki links.
- Put media in `wiki/media/` and reference it with paths such as `/wiki/media/image.png`.
- A player-visible page needs both `visibility: players` and `approvalStatus: approved`.
- Wrap private sections in `:::gm` blocks; CampaignRepo strips them from player views.
- After editing or pushing files outside the app, use **Refresh repo** to reload source, rebuild indexes, and update the open campaign view.
- Use **Repair indexes** in campaign settings or the Health center if generated state still disagrees with the source files.

Player visibility applies inside CampaignRepo. Anyone with access to the raw repository can read its files, including GM notes.

## About This Archive

This is a campaign content repository. CampaignRepo's application source, installation instructions, and feature documentation are maintained in the [CampaignRepo repository](https://github.com/avorial/CampaignRepo).
