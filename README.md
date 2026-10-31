# Skills

Agent skills by [Jasper van Puffelen López](https://jaspervpl.com), AI engineer. Each folder is a skill in the open [Agent Skills](https://agentskills.io) format: a `SKILL.md` with instructions that any compatible agent can load.

| Skill | What it does |
|---|---|
| [ai-overviews-writer](ai-overviews-writer/SKILL.md) | Plans, drafts and checks articles so people trust them and AI search (Google AI Overviews, ChatGPT, Perplexity, Claude) can cite them. It starts with a briefing and never drafts without a first-hand element from the author. |

## Install

- **Claude Code:** copy the skill folder to `~/.claude/skills/` (for all your projects) or to `.claude/skills/` inside a project.
- **Claude apps:** download the `.zip` from the [releases](https://github.com/TARCONI-ai/skills/releases) or from [jaspervpl.com/resources](https://jaspervpl.com/resources/) and upload it in the Skills section of the settings.
- **Other agents:** any agent that supports the Agent Skills standard can load the folder. Check its documentation for where skills go.

## Why this skill

In 2025 I built a custom GPT that wrote articles with a fixed structure for AI Overviews. The structure worked for machines, but without the author's own experience and a human review the articles came out generic. This skill keeps the structure and adds what was missing: a briefing that asks for first-hand material, and a checklist the author reviews before publishing.

## License

[MIT](LICENSE)
