<p align="center">
  <img src="https://raw.githubusercontent.com/brain-bootstrap/.github/main/profile/brain-bootstrap-logo.svg" alt="Brain Bootstrap" width="480" />
</p>
<p align="center"><em>Your AI assistant is brilliant. It just resets every session, ignores your conventions, and reinvents your patterns.<br><strong>Brain Bootstrap fixes that — permanently.</strong></em></p>

<p align="center">
  <a href="https://github.com/brain-bootstrap/claude-code-brain-bootstrap"><img src="https://img.shields.io/badge/Claude_Code-Ready-6B21A8?style=flat-square" alt="Claude Code"></a>
  &nbsp;
  <a href="https://github.com/brain-bootstrap/copilot-brain-bootstrap"><img src="https://img.shields.io/badge/GitHub_Copilot-Ready-6e40c9?style=flat-square&logo=github" alt="GitHub Copilot"></a>
  &nbsp;
  <a href="https://github.com/brain-bootstrap/codex-brain-bootstrap"><img src="https://img.shields.io/badge/OpenAI_Codex-Ready-10A37F?style=flat-square" alt="OpenAI Codex"></a>
  &nbsp;
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="MIT License">
</p>

---

You ask your AI to add a feature. It uses the wrong build command. It reinstalls a utility you already have. It edits the config file you told it never to touch.

You correct it. It apologizes. **Next session: same mistakes.**

AI coding tools are stateless by design — every session starts blank. So you become the AI's memory: re-explaining your stack, re-enforcing your rules, re-correcting the same errors. Session after session.

**Brain Bootstrap ends that loop.**

It's a project configuration template — a folder of files you install once into your repo. From that point on, your AI assistant knows your codebase, respects your rules, and carries its knowledge forward permanently. **It learns your way and keeps it.**

---

## ⚡ How it works

**1. Install** — Copy the template into your repo with a single command. No cloud, no account, no daemon. Just files in your repository.

**2. Bootstrap** — Run `/bootstrap` once. The discovery engine scans your codebase across 30+ languages and frameworks, auto-detects your stack, and has the AI generate your architecture docs, domain glossary, build conventions, and task templates — specific to _your_ project. Takes about 5 minutes.

**3. Every session after that** — your AI loads your full context automatically. It knows your stack, your rules, and your patterns before you type the first word.

> **One knowledge layer, every tool.** Write your conventions once — Claude Code, Copilot, and Codex all read the same context files. Switch tools without re-teaching anything.

---

## ✨ What actually changes

| Before Brain Bootstrap                                            | After                                                                    |
| :---------------------------------------------------------------- | :----------------------------------------------------------------------- |
| Re-explain your stack, build commands, and patterns every session | Stack and conventions loaded automatically at every session start        |
| AI ignores your rules — wrong files touched, wrong commands run   | Hooks intercept AI actions and block rule violations before they execute |
| Correct the same mistake once per session, forever                | One correction updates permanent memory — never repeated                 |
| Architecture docs written manually, drift immediately             | AI writes and maintains living docs from real code, on every change      |

---

## 🤖 Pick your tool

| Tool               | Repo                                                                                          | What you get                                                                                                                     |
| :----------------- | :-------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------- |
| **Claude Code**    | [claude-code-brain-bootstrap](https://github.com/brain-bootstrap/claude-code-brain-bootstrap) | Full slash-command workflow — 31 `/commands`, 5 subagents for review/research/planning, 16 enforcement hooks, 49 reusable skills |
| **GitHub Copilot** | [copilot-brain-bootstrap](https://github.com/brain-bootstrap/copilot-brain-bootstrap)         | Chat-native power — 38 `/prompts`, 5 agents, 7 hooks wired into VS Code, 49 skills                                               |
| **OpenAI Codex**   | [codex-brain-bootstrap](https://github.com/brain-bootstrap/codex-brain-bootstrap)             | Terminal-first depth — 49 skills, 10 lifecycle hooks, 5 subagents, headless-ready                                                |

---

## 🚀 Get started in two steps

**Step 1 — Install the template into your repo**

```bash
# Claude Code
git clone https://github.com/brain-bootstrap/claude-code-brain-bootstrap.git /tmp/brain
bash /tmp/brain/install.sh /path/to/your-repo
rm -rf /tmp/brain

# GitHub Copilot
git clone https://github.com/brain-bootstrap/copilot-brain-bootstrap.git /tmp/copilot-brain
bash /tmp/copilot-brain/install.sh /path/to/your-repo
rm -rf /tmp/copilot-brain

# OpenAI Codex
git clone https://github.com/brain-bootstrap/codex-brain-bootstrap.git /tmp/codex-brain
bash /tmp/codex-brain/install.sh /path/to/your-repo
rm -rf /tmp/codex-brain
```

**Step 2 — Let the AI configure itself**

Open your AI assistant in the repo and run the bootstrap command:

```
/bootstrap          ← Claude Code & GitHub Copilot
$bootstrap          ← OpenAI Codex
```

The discovery engine scans your repo, fills every placeholder, and produces architecture docs and domain knowledge tailored to your codebase. **Fully automated — no manual editing required.**

That's it. Your AI assistant now knows your project.

---

<p align="center">
  <sub>No third-party installs without your explicit approval · Works with any language, any stack · MIT License</sub>
</p>
