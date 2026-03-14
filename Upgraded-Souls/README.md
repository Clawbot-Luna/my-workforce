# Upgraded Souls

These are upgraded versions of the coding team agent souls, generated after a post-mortem on the AI Idle Factory project (March 14, 2026).

**Original souls are untouched.** These live here as drop-in replacements when you're ready to upgrade.

## What Changed

The core problem identified: agents were completing tasks in isolation without end-to-end validation of the final integrated product. Fixes were applied to individual modules but never verified against the running browser UI, causing repeated regressions across releases.

## Upgraded Agents

| File | Role | Key Additions |
|------|------|---------------|
| `coding-lead-upgraded.md` | Orchestrator | Final integration gate before marking complete; API contract enforcement |
| `coding-dev-upgraded.md` | Developer | Mandatory smoke test after every UI/integration change; workspace sync protocol |
| `coding-test-upgraded.md` | Tester | End-to-end UI test requirement; no PASS without exercising actual built artifact |
| `coding-qa-upgraded.md` | QA | Pre-release checklist must include running final HTML, not just code review |
| `coding-research-upgraded.md` | Researcher | Must document and share API contracts before dev begins |

## How to Apply

Replace the corresponding `SOUL.md` file in `~/.openclaw/workspace-[agent]/SOUL.md` with the upgraded version, then restart the gateway.
