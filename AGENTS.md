# AGENTS.md

Rules for AI agents working in this repo. Human-facing overview: `README.md`.

- **What is here:** only PDFs (`anurag_gupta_cv.pdf`, `anurag_gupta_cv_.pdf`, and `WebpeInternship/`).
  There is no code, build or test suite.
- **Do not touch:** do not edit, rename, delete or regenerate the PDFs unless the owner asks. They are
  personal documents. Do not copy their contents into other repos, logs, issues or PR text.
- **Secrets:** never read `.env*` files or credentials.
- **Workflow:** work in a git worktree, not the main checkout; commit with path-scoped adds; open a PR
  against `main`. Commit hooks (gitleaks) must pass and are never bypassed.
