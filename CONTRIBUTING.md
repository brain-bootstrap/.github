# Contributing to Brain Bootstrap

Thank you for helping make AI coding better for everyone.

Brain Bootstrap is a universal project template — all contributions must remain **domain-agnostic** (no project-specific content). The goal is a template that works for any repo, any language, any team.

## What you can contribute

| Area                  | Examples                                                     |
| :-------------------- | :----------------------------------------------------------- |
| 📚 Documentation      | Fix a typo, improve clarity, add a worked example            |
| 🔍 Stack detection    | New language, framework, or package manager in `discover.sh` |
| 🪝 Lifecycle hooks    | New safety patterns or quality gates                         |
| ⚡ Commands / Prompts | New workflow for slash commands or prompt files              |
| 🤖 Skills / Agents    | New AI skill or specialist agent                             |
| 🐛 Bug fixes          | Something broken? Fix it                                     |

## Where to contribute

Each tool has its own repo — contribute to the one that matches your AI assistant:

- **Claude Code** → [claude-code-brain-bootstrap](https://github.com/brain-bootstrap/claude-code-brain-bootstrap)
- **GitHub Copilot** → [copilot-brain-bootstrap](https://github.com/brain-bootstrap/copilot-brain-bootstrap)
- **OpenAI Codex** → [codex-brain-bootstrap](https://github.com/brain-bootstrap/codex-brain-bootstrap)

## How to contribute

1. **Fork** the relevant repo
2. **Create a branch**: `git checkout -b feat/your-feature`
3. **Make your changes** — keep them focused on one thing
4. **Test**: run `bash validate.sh` to confirm nothing is broken
5. **Open a PR** with a clear description of what you changed and why

## Guidelines

- Keep changes surgical — don't refactor unrelated code
- All scripts must be POSIX-compatible (bash 3.2+, no `pipefail` or `errexit` by default)
- New hooks must be deterministic — no AI reasoning, no network calls
- Cross-platform: test on Linux and macOS if touching shell scripts

## Questions?

Open a [Discussion](https://github.com/orgs/brain-bootstrap/discussions) — we're happy to help.
