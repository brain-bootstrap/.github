<p align="center">
  <img src="https://img.shields.io/badge/ᗺB-Brain%20Bootstrap-6B21A8?style=for-the-badge&labelColor=1e1b4b" alt="ᗺB Brain Bootstrap" />
</p>

<h1 align="center">ᗺB Brain Bootstrap</h1>
<p align="center"><em>Give your AI coding assistant the one thing it's missing: a persistent brain.</em></p>

---

**Brain Bootstrap is a project configuration template you install once into your repo.**

It gives your AI coding assistant persistent memory, enforced guardrails, and ready-to-use workflows — so it finally knows your codebase, respects your rules, and stops repeating the same mistakes every session.

**You correct it once. It never makes that mistake again.**

---

## Pick your tool

| Tool               | Repo                                                                                          | What you get                                           |
| :----------------- | :-------------------------------------------------------------------------------------------- | :----------------------------------------------------- |
| **Claude Code**    | [claude-code-brain-bootstrap](https://github.com/brain-bootstrap/claude-code-brain-bootstrap) | 31 slash commands · 18 skills · 16 hooks · 5 subagents |
| **GitHub Copilot** | [copilot-brain-bootstrap](https://github.com/brain-bootstrap/copilot-brain-bootstrap)         | 38 prompt files · 18 skills · 7 hooks · 5 agents       |
| **OpenAI Codex**   | [codex-brain-bootstrap](https://github.com/brain-bootstrap/codex-brain-bootstrap)             | 48 skills · 10 hooks · 5 subagents                     |

All three share the same knowledge layer — write your conventions once, every tool benefits.

---

## How it works

Most AI coding tools read your instructions. None of them enforce those instructions on themselves.

Brain Bootstrap replaces text hints with mechanisms:

- **Persistent memory** — your conventions, architecture decisions, and past corrections embedded in project config files, never forgotten across sessions
- **Enforced rules** — deterministic bash hooks that block violations before they run, zero AI judgment involved
- **Ready-to-use workflows** — skills and commands for code review, planning, debugging, MR generation and more
- **Self-updating knowledge** — the knowledge layer grows as your codebase evolves, session by session

---

## Get started

```bash
# Claude Code
bash <(curl -fsSL https://raw.githubusercontent.com/brain-bootstrap/claude-code-brain-bootstrap/main/install.sh) /path/to/your-repo

# GitHub Copilot
bash <(curl -fsSL https://raw.githubusercontent.com/brain-bootstrap/copilot-brain-bootstrap/main/install.sh) /path/to/your-repo

# OpenAI Codex
bash <(curl -fsSL https://raw.githubusercontent.com/brain-bootstrap/codex-brain-bootstrap/main/install.sh) /path/to/your-repo
```

---

<p align="center">
  <sub>MIT License · No third-party installs without your explicit approval · Works with any language, any stack</sub>
</p>
