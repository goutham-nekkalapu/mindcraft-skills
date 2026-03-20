# 🧠 mindcraft-skills

> A growing collection of open-source Claude skills for clearer thinking.

These skills extend Claude with reusable, high-quality workflows for reasoning,
analysis, and communication. They follow the
[Agent Skills open standard](https://skills.sh) — compatible with Claude Code,
OpenClaw, Cursor, Cline, Codex, and more.

---

## Install

**One command — works across all supported agents:**

```bash
npx skills add goutham-nekkalapu//mindcraft-skills
```

**Install a specific skill:**

```bash
npx skills add goutham-nekkalapu//mindcraft-skills --skill prompt-archeologist
```

**Claude Code (manual):**

```bash
git clone https://github.com/goutham-nekkalapu//mindcraft-skills
cp -r mindcraft-skills/prompt-archeologist ~/.claude/skills/
```

**claude.ai:**

1. Download the `.skill` zip from [Releases](https://github.com/goutham-nekkalapu//mindcraft-skills/releases)
2. Go to **Settings → Capabilities → Skills → Upload**

---

## Skills

| Skill | What it does | Status |
|---|---|---|
| [prompt-archeologist](#-prompt-archeologist) | Reverse-engineers reusable prompts from messy conversations | ✅ Available |

- More coming soon ..
---

## Skill details

### 🏺 prompt-archeologist

Reverse-engineers high-quality, reusable prompts from messy conversations or
rough descriptions.

**Triggers when you say things like:**
- "Turn what we just did into a prompt"
- "How do I ask this again?"
- "I want to recreate this later"
- "What prompt should I use for this?"

**What you get:** A named, parameterized, copy-paste-ready prompt with
excavation notes explaining the assumptions made.

```bash
# Install just this skill
npx skills add goutham-nekkalapu//mindcraft-skills --skill prompt-archeologist
```

---

## Philosophy

These skills are built around one idea: **most people know what they want but
can't articulate it precisely on the first try.** Good skills bridge that gap —
they surface intent, encode it clearly, and make it repeatable.

Each skill follows three design principles:

- **Generic enough** to be useful to a wide audience
- **Specific enough** to actually do something well
- **Transparent** — you can read exactly what the skill instructs Claude to do

---

## Contributing

Contributions welcome. If you have a skill idea or improvement:

1. Fork this repo
2. Create a folder: `your-skill-name/SKILL.md`
3. Follow the [Agent Skills spec](https://skills.sh/docs)
4. Open a PR with a short description of what it does and why

Please include at least one example of the skill in action in your PR
description.

---

## License

MIT — free to use, modify, and redistribute.

---

