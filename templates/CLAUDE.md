# [Your Name]'s Second Brain

This is your personal AI knowledge system. Everything your AI needs to work with you is contained here.

## On every session start

1. Read this file first
2. Read `index.md` to understand what's where
3. Read `me/thinking.md` to know what's top of mind
4. Read `me/preferences.md` for behavior rules
5. Load other files as relevant to the current task

## Who I am

See `me/profile.md` for full details.

<!-- Customize: Add a 1-2 sentence summary of who you are and what you do -->

## Behavior rules

See `me/preferences.md` for full details.

<!-- Customize: Add your top 3-5 rules here. Examples: -->
<!-- - Be direct and concise -->
<!-- - Output files, not conversation -->
<!-- - Challenge my thinking when appropriate -->

## Folder structure

```
brain/
├── CLAUDE.md          # You are here
├── index.md           # What's where
├── me/                # Who I am (identity, preferences, thinking)
├── work/              # Current projects and context
├── ideas/             # Seeds, connections, things to develop
├── reference/         # Published work, articles, external material
├── research/          # Deeper research and analysis
├── inbox/             # Raw inputs to process
├── tasks/             # To-dos and priorities
├── skills/            # Processing workflows
├── drafts/            # Work in progress
├── meetings/          # Processed meeting notes
└── archive/           # Completed/processed items
```

## Knowledge hierarchy

When the same topic appears in multiple places, this determines authority:

1. **Canonical** (highest): `me/profile.md`, published positions
2. **Frontier**: `me/thinking.md` (where my head is right now)
3. **Working context**: `work/` files (current projects, domain intel)
4. **Raw material**: `ideas/`, `drafts/`, `reference/` (supporting, not authoritative)

When writing or answering questions, prefer higher-level sources.

## Processing rules

### Inbox
When items arrive in `inbox/`:
1. Determine type and extract: ideas to `ideas/`, tasks to `tasks/`, insights to relevant files
2. Wire knowledge into active thinking (don't just file it)
3. Move processed item to `archive/`

### Meetings
1. Create structured notes in `meetings/`
2. Extract decisions, action items, key insights
3. Route tasks to `tasks/`
4. Update affected project files and `me/thinking.md`

### Tasks
When complete, delete from `tasks/tasks.md`. Git history preserves what was done.

## Updating this system

This is a living system. Update files as knowledge evolves. Keep `index.md` current when structure changes.
