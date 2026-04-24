<p align="center">
  <img src="https://raw.githubusercontent.com/brain-bootstrap/.github/main/profile/brain-bootstrap-logo.svg" alt="Brain Bootstrap" width="480" />
</p>
<p align="center"><em>Your AI assistant is brilliant. It just forgets everything between sessions.<br><strong>Brain Bootstrap fixes that — permanently.</strong></em></p>

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

It's a project configuration template — a folder of files you install once into your repo. From that point on, your AI assistant knows your codebase, respects your rules, and carries its knowledge forward permanently. **One correction is the last correction.**

---

## 🤖 Pick your tool

| Tool               | Repo                                                                                          | What you get                                           |
| :----------------- | :-------------------------------------------------------------------------------------------- | :----------------------------------------------------- |
| **Claude Code**    | [claude-code-brain-bootstrap](https://github.com/brain-bootstrap/claude-code-brain-bootstrap) | 31 slash commands · 18 skills · 16 hooks · 5 subagents |
| **GitHub Copilot** | [copilot-brain-bootstrap](https://github.com/brain-bootstrap/copilot-brain-bootstrap)         | 38 prompt files · 18 skills · 7 hooks · 5 agents       |
| **OpenAI Codex**   | [codex-brain-bootstrap](https://github.com/brain-bootstrap/codex-brain-bootstrap)             | 48 skills · 10 hooks · 5 subagents                     |

> All three share the same knowledge layer — write your conventions once, every tool benefits.

---

## ✨ What actually changes

| Before Brain Bootstrap                       | After                                                        |
| :------------------------------------------- | :----------------------------------------------------------- |
| Explain your stack every session             | Explained once, remembered forever                           |
| AI ignores your rules                        | Rules enforced by hooks before execution                     |
| Docs drift, context floods, PRs break things | Docs stay current, context is managed, blast radius is known |
| You babysit the AI                           | The AI runs itself                                           |

---

## 🚀 Get started in two steps

**Step 1 — Install the template into your repo**

```bash
# Claude Code
bash <(curl -fsSL https://raw.githubusercontent.com/brain-bootstrap/claude-code-brain-bootstrap/main/install.sh) /path/to/your-repo

# GitHub Copilot
bash <(curl -fsSL https://raw.githubusercontent.com/brain-bootstrap/copilot-brain-bootstrap/main/install.sh) /path/to/your-repo

# OpenAI Codex
bash <(curl -fsSL https://raw.githubusercontent.com/brain-bootstrap/codex-brain-bootstrap/main/install.sh) /path/to/your-repo
```

**Step 2 — Let the AI configure itself**

Open your AI assistant in the repo and run the bootstrap command:

```
/bootstrap          ← Claude Code & GitHub Copilot
$bootstrap          ← OpenAI Codex
```

The bootstrap command runs the discovery engine, auto-detects your entire stack, fills all placeholders, and has the AI write architecture docs and domain knowledge specific to your codebase. **Fully automated — takes about 5 minutes.**

That's it. Your AI assistant now knows your project.

---

<p align="center">
  <sub>No third-party installs without your explicit approval · Works with any language, any stack · MIT License</sub>
</p>
