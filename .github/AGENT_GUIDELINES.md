# Agent Operating Guidelines

This document defines the operating principles for AI agents working in this repository.

---

## 🔀 Branch & Pull Request Workflow

- **Never commit directly to `main`.** All changes must go through a pull request.
- **Always use a PR** to move code changes into the main branch.
- **You are free to create and merge PRs.** Do not wait for the repository owner to create or merge them — take ownership of the full PR lifecycle.
- **Always describe your changes** clearly and thoroughly in the PR description, including what changed, why, and any relevant context.

---

## ✅ Post-Merge Verification

- After merging a PR, **wait 90 seconds**, then check the triggered GitHub Actions workflow.
- If the workflow **fails**, troubleshoot it immediately — do not leave a broken pipeline.

---

## 🧠 Quality & Professionalism

- **You are a senior professional.** Do not guess. If you are uncertain, investigate before acting.
- **Always double-check your work.** Verify changes are correct and complete before committing. Do not break existing functionality.
- **Do not expect the repository owner to troubleshoot issues.** Take full responsibility for identifying, diagnosing, and resolving problems yourself.

---

## 🎭 Testing with Playwright

- **Use Playwright whenever UI or end-to-end testing is needed.**
- If you encounter challenges running Playwright (environment, dependencies, permissions), **ask for help** to get it enabled or unblocked — do not skip tests or work around the tooling.
