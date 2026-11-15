# BIOGLOW Innovation Project: the spotted lanternfly

FIRST LEGO League 2026–27 (BIOGLOW). The team noticed fewer spotted lanternflies in 2026. The plan:

1. Research why people think the numbers dropped.
2. Use that research to interview experts, who can confirm the explanations or offer others.
3. Write protocols for keeping lanternfly numbers down in the years ahead.

This folder holds what one Claude Code session produced on 2026-11-15 for steps 1 and 2.

## Live versions

The deck and the prep kit live on claude.ai. Edits made there do not update this folder, and edits made here do not update them.

| What | Link | Copy in this folder |
| --- | --- | --- |
| Interview deck (16 slides, with speaker notes) | https://claude.ai/artifact/M2X3pz8DLpvanHCsd3ZSsf | `deck/` (source files) and `deck/previews/` (images) |
| Team prep kit (reading, fact cards, practice questions, answer key) | https://claude.ai/artifact/LbsfxyHLtBTsjkNgoRGJWA | `prep-kit.md` |

Both links are private until they are shared from the page's Share menu.

## What is here

- `research-notes.md`: the findings, the sources, and what was and was not verified. Read this first.
- `prep-kit.md`: the kit the kids work through so they can defend the deck. It was exported from the live doc on 2026-11-15.
- `deck/project/`: the deck's source. `deck.json` gives the slide order, `deck.css` holds the shared styles, and `slides/*.html` has one file per slide, with speaker notes in each `<aside>`.
- `deck/previews/`: contact sheets of all 16 slides, four slides per image.

## Picking this up in a new Claude Code session

Open Claude Code in this repo and start with:

> Read bioglow-lanternfly/README.md and research-notes.md. We are continuing the lanternfly Innovation Project.

To change the live deck, the new session publishes the edited files under `deck/project/` back to the deck's link with the Artifact tool. To change the prep kit, it edits the live doc with the Claude Docs tools and then re-exports `prep-kit.md`.

## Open items

- Fill in the blue `[placeholders]` in the deck: team name, town, date, coach email and the team's own sightings on slide 2.
- Work through the "Fix before the interview" table in `prep-kit.md`. It lists seven spots in the deck that need a source or a wording change.
- Decide on the evidence ratings on slide 12. They were drafted by Claude, and the team should agree with them or change them.
- After the expert interviews, rewrite slide 14 (protocols) based on what the experts said.
