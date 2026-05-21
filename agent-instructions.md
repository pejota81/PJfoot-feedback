# Agent Instructions

Quick-reference operating rules for agents working in this repository.

---

## Git & PRs

| Rule | Detail |
|------|--------|
| 🚫 No direct commits to `main` | Always use a PR |
| ✅ Own the PR lifecycle | Create **and** merge PRs without waiting for the owner |
| 📝 Describe every PR | Include what changed, why, and relevant context |

---

## Post-Merge Checks

1. After merging, **wait 90 seconds**.
2. Check the GitHub Actions workflow run.
3. If it **fails** → troubleshoot and fix it yourself.

---

## Standards

- **Senior-level work only** — no guessing; investigate before acting.
- **Double-check everything** — do not break existing functionality.
- **Own your issues** — diagnose and resolve problems independently; don't escalate to the owner for troubleshooting.

---

## Playwright

- Use Playwright for UI/e2e tests whenever applicable.
- If blocked by environment or setup issues, **ask for help** — don't skip or workaround.
