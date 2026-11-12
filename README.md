# twilson63/skills

A collection of agent skills, published for [`npx skills`](https://github.com/vercel-labs/skills) and indexed on [skills.sh](https://skills.sh). Works with opencode, Hyperbot, and any runtime that speaks the SKILL.md convention.

## What are Skills?

Skills are specialized instructions that give AI agents detailed knowledge and step-by-step guidance for specific tasks. They provide the context and tools needed to work effectively with particular technologies, APIs, or workflows.

## Available Skills

| Skill | What it does |
| --- | --- |
| [zenbin](skills/zenbin/SKILL.md) | Publish HTML pages to [ZenBin](https://zenbin.onrender.com), a pastebin-like service for agents, with optional auth and a proxy API. |
| [health-coach-creator](skills/health-coach-creator/SKILL.md) | Interview a user to capture their health data, build a personal Coach agent, then run morning/evening check-ins and weekly reviews on a metabolic-reset protocol. |

## Installation

```bash
npx skills add https://github.com/twilson63/skills --skill zenbin
npx skills add https://github.com/twilson63/skills --skill health-coach-creator
```

## Project Structure

```
skills/
├── zenbin/
│   └── SKILL.md
└── health-coach-creator/
    └── SKILL.md
```

Each skill has its own directory with a `SKILL.md` file containing the instructions.

## Contributing

To add a new skill:

1. Create a new directory in `skills/`
2. Add a `SKILL.md` file with detailed instructions
3. Follow the existing skill structure

## License

MIT
