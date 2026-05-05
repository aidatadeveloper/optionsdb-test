# GitHub Repo Reference — optionsdb-test

**URL:** https://github.com/aidatadeveloper/optionsdb-test
**Visibility:** public
**Standard:** ~/.claude/educational/GITHUB_PROJECT_STANDARD.md

## What this is

Static HTML/JS test fixture for optionsdatabase.com — includes screeners/, strategies/, tickers/ test data. Used for cross-device QA via GitHub Pages.

## What's gitignored

Per the standard at `~/.claude/educational/GITHUB_PROJECT_STANDARD.md`:
- Secrets: `.env`, `**/credentials*`, `**/*.pem`, `**/*.key`, `**/*.token`, `**/*.secret`, `**/tokens.json`
- Python: `__pycache__/`, `.venv/`, `*.pyc`
- Node: `node_modules/`
- Logs: `logs/`, `*.log`
- OS / editor: `Thumbs.db`, `.DS_Store`, `.vscode/`, `.idea/`
- Claude Code per-user cache: `.claude/`

## Common workflow

```bash
git add <files>
git commit -m "<imperative summary>"
git push origin main
```
