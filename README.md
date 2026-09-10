# NMR Season 2

Development repository for **No Man's Road — Season 2**.

## Repository Structure

```text
NMR-Season-2/
├─ 01-Server-Setup/
├─ 02-General-TODO-List/
│  └─ README.md
├─ 03-S01-Mod-List/
│  └─ TODO.md
├─ 04-Game-Progression/
│  └─ TODO.md
├─ 05-Storyline-Main-Quest-Line/
│  ├─ 01-Foundations.md
│  ├─ 02-Timeline.md
│  ├─ 03-Chapters.md
│  ├─ 04-Quest-Progression.md
│  ├─ 05-Locations.md
│  ├─ 06-Lore-Documents.md
│  ├─ 07-AI-Bosses.md
│  └─ TODO.md
├─ 06-Factions/
│  └─ TODO.md
├─ 07-Side-Quests/
│  ├─ 01-Hunter-Quests/
│  ├─ 02-Medic-Quests/
│  ├─ 03-Bandit-Quests/
│  └─ TODO.md
├─ 08-Locations-Custom-Areas/
│  └─ TODO.md
├─ 09-Events/
│  ├─ Event-Mod-List.md
│  └─ TODO.md
├─ 10-Economy-Traders/
│  └─ TODO.md
├─ 11-Weapons/
│  └─ TODO.md
├─ 12-Building-Building-Items/
│  └─ TODO.md
├─ 13-Vehicles/
│  └─ TODO.md
├─ README.md
└─ CHANGELOG.md
```

## Working Rules

- **Storyline & Main Quest Line** may contain detailed story, lore and main-quest design discussion.
- All other sections use short, action-based checklist / TODO entries.
- **Server Setup** contains only finalized server-side implementation tasks transferred from Season 2 design decisions.
- Any topic that has **not** been transferred to **Server Setup** is considered an **open decision / open design topic**.
- No separate **Open Decisions** file is maintained.
- Each top-level project section except **Server Setup** and **General TODO List** has one section-level `TODO.md` file.
- Subfolders do not have separate TODO files unless explicitly agreed later.
- **General TODO List** is maintained in `02-General-TODO-List/README.md` as the consolidated summary of all section-level TODO files and will mirror their items under the relevant section heading with a link to the source TODO file.
- **S01 Mod List** contains the Season 1 mod inventory and the working Season 2 review / replacement decisions.
- Gameplay or narrative decisions that do not require server configuration remain in their design section.
- New headings and subfolders are added only after they are agreed.
