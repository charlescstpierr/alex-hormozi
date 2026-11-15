# Alex Hormozi (unofficial distillation)

This repository is a skill that speaks as Alex Hormozi, in first person, from his public videos, writing, and posts. It is not Alex Hormozi, and it is not endorsed by him.

## What it is

An unofficial persona skill. Once loaded, an agent answers as Alex Hormozi, using the voice, opinions, and boundaries in this repo:

- `ENTRY.md` — who he is, how to answer, and what to say if asked whether this is really him
- `VOICE.md` — how he sounds, plus exact quotes
- `OPINIONS.md` — positions he has taken in public
- `BOUNDARIES.md` — limits he has actually stated

The material comes from public sources: his X posts, the free audiobook versions of his books that he reads himself and released on his official podcast The Game, solo episodes of that podcast, and only his speaker-labeled turns from interviews. It is a distillation of public speech, not a private or official channel.

## How to add this repo as a skill

The loader lives at `skills/alex-hormozi/SKILL.md`. It fetches the four files above from this repository (GitHub raw, with a jsDelivr fallback).

1. Clone the repository:

   ```bash
   git clone https://github.com/charlescstpierr/alex-hormozi.git
   ```

2. Copy or link the skill folder into your agent's skills directory, for example:

   - Cursor: `~/.cursor/skills/alex-hormozi` or `<project>/.cursor/skills/alex-hormozi`
   - Claude Code / Agent Skills: `.claude/skills/alex-hormozi` or `~/.claude/skills/alex-hormozi`

   ```bash
   mkdir -p ~/.cursor/skills
   cp -R alex-hormozi/skills/alex-hormozi ~/.cursor/skills/alex-hormozi
   ```

   If your tool can install a skill directly from a GitHub repository, point it at `https://github.com/charlescstpierr/alex-hormozi`.

3. After that, ask the agent to talk as Alex Hormozi. It should load this skill and answer in character.
