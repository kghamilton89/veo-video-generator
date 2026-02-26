# clawhub-skills

A monorepo of **ClawHub skills** for [OpenClaw](https://clawdhub.com) agents developed by [Kenneth Hamilton](https://kennethhamilton.me).

Each skill lives in its own subdirectory and is self-contained — with its own `SKILL.md`, `package.json`, and source files. This structure lets every skill be published, versioned, and installed independently via [ClawHub](https://clawhub.ai).

## Repository Structure

```bash
clawhub-skills/
├── README.md                  ← you are here
└── veo-video-generator/       ← skill: Veo Video Generator
    ├── SKILL.md
    ├── generate.js
    ├── package.json
    ├── package-lock.json
    └── README.md
```

## Skills

| Skill | Description | ClawHub |
|---|---|---|
| [veo-video-generator](./veo-video-generator/README.md) | Generate cinematic 1080p videos with synced audio using Google Veo 3.1 | [View on ClawHub](https://clawhub.ai/kghamilton89/veo-video-generator) |

## Adding a New Skill

1. Create a new folder at the repo root with your skill's name (e.g. `my-new-skill/`).
2. Add a `SKILL.md` file following the `metadata.clawdbot` schema.
3. Add a `README.md`, source files, and a `package.json` (if needed).
4. Update the **Skills** table above with a link to the new skill's README.

## License

MIT © 2026
