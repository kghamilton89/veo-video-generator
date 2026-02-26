# clawhub-skills

A monorepo of **ClawHub skills** for [OpenClaw](https://clawdhub.com) agents developed by [Kenneth Hamilton](https://kennethhamilton.me).

Each skill lives in its own subdirectory and is self-contained — with its own `SKILL.md`, `package.json`, and source files. This structure lets every skill be published, versioned, and installed independently via [ClawHub](https://clawhub.ai).

## Repository Structure

```bash
clawhub-skills/
├── README.md                  ← you are here
├── brave-web-search/          ← skill: Brave Web Search
│   ├── SKILL.md
│   ├── index.js
│   └── package.json
└── veo-video-generator/       ← skill: Veo Video Generator
    ├── SKILL.md
    ├── generate.js
    ├── package.json
    └── package-lock.json
```

## Skills

| Skill | Description | ClawHub |
|---|---|---|
| [brave-web-search](./brave-web-search/SKILL.md) | Search the web and get AI-summarized answers using the Brave Search API | [View on ClawHub](https://clawhub.ai/kghamilton89/brave-web-search) |
| [veo-video-generator](./veo-video-generator/SKILL.md) | Generate cinematic 1080p videos with synced audio using Google Veo 3.1 | [View on ClawHub](https://clawhub.ai/kghamilton89/veo-video-generator) |

## Adding a New Skill

1. Create a new folder at the repo root with your skill's name (e.g. `my-new-skill/`).
2. Add a `SKILL.md` file following the `metadata.clawdbot` schema.
3. Add source files and a `package.json` (if needed).
4. Update the **Skills** table above with a link to the new skill's `SKILL.md`.

## License

MIT © 2026
