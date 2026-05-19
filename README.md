<!--
Author: Alexander Ford <alex@pseudo-lang.com>
Repository: https://github.com/alexander-ford-ventures/project-architect
License: MIT
-->

# ⚠️  This repository has moved

> **`siliconyouth/project-architect` is now a frozen legacy mirror.**
> All future development happens at **[`alexander-ford-ventures/project-architect`](https://github.com/alexander-ford-ventures/project-architect)**.

---

## Why

As of **v3.0.0 (2026-05-19)** the canonical home for `project-architect` is the [`alexander-ford-ventures`](https://github.com/alexander-ford-ventures) organization. Ownership and maintainership transferred to **Alexander Ford** `<alex@pseudo-lang.com>` (Alexander Ford Ventures).

This repository is preserved **read-only** as a historical record of every release up to and including `v2.3.0`. New tags, releases, issues, and PRs all go to the new home.

## Migrate your install

If you previously installed via `project-architect@siliconyouth`, switch to the new marketplace identifier:

```bash
claude plugin uninstall project-architect@siliconyouth
claude plugin marketplace remove siliconyouth                                  # optional cleanup
claude plugin marketplace add alexander-ford-ventures/project-architect
claude plugin install project-architect@alexander-ford-ventures
/reload-plugins
```

After re-installing, the **Preflight version-freshness check** in any new Claude Code session will point at the canonical repo and surface future updates automatically.

## What lives on the new repo

Everything you knew, in the same shape. The `v3.0.0` release is identity-only — no behaviour, API, or schema changes. Same 11-phase orchestrator, same 6 specialised subagents, same 16-check quality-gate auditor, same 68 tests still green. See the [v3.0.0 release notes](https://github.com/alexander-ford-ventures/project-architect/releases/tag/v3.0.0) for the full changelog of the move.

## Historical tags

The v2.0.0 → v2.3.0 release history of this `siliconyouth/project-architect` mirror is preserved as-is and remains browsable from the GitHub **Tags** dropdown. The same tags also live on the new canonical repository — `git fetch` either remote and they resolve to the same commits.

---

*★ Skillfully made with [project-architect](https://github.com/alexander-ford-ventures/project-architect).*
