# Security Policy

## Supported versions

| Repo                        | Supported version |
| :-------------------------- | :---------------- |
| claude-code-brain-bootstrap | `v1.0.0` (latest) |
| copilot-brain-bootstrap     | `v1.0.0` (latest) |
| codex-brain-bootstrap       | `v1.1.0` (latest) |

Only the latest stable release of each repo receives security fixes.

## Reporting a vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

Email **security@brain-bootstrap.dev** (or open a [private security advisory](https://github.com/brain-bootstrap/claude-code-brain-bootstrap/security/advisories/new) on the relevant repo).

Include:

- Which repo and version is affected
- A description of the vulnerability and its impact
- Steps to reproduce (if applicable)

You'll receive an acknowledgement within 48 hours and a resolution timeline within 7 days.

## Scope

Brain Bootstrap installs **configuration files only** — no binaries, no runtime dependencies, no network calls during normal operation. The attack surface is limited to:

- Shell scripts run at install time (`install.sh`, `validate.sh`, `setup-plugins.sh`)
- Lifecycle hooks that execute bash scripts at AI session events

If you discover a way these scripts could be exploited (e.g. path traversal, command injection via template variables), please report it.
