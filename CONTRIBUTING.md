# Contributing to Knowledge Stream Projects

## 🔄 Workflow

1. **Pick a task** — check GitHub Projects or assigned issues
2. **Create a branch** from `main`:
    git checkout -b feature/KS-123-short-description
3. **Write code** — follow project conventions
4. **Push and open PR** — link the issue:
    Fixes #123
5. **Wait for review** — at least 1 approval required
6. **Merge** — squash merge preferred
7. **Delete branch** after merge

## 📛 Branch Naming
[type]/[issue-number]-[short-description]

Examples:
- `feature/KS-42-user-dashboard`
- `fix/KS-87-api-timeout`
- `hotfix/KS-99-prod-crash`

## ✅ PR Rules

- No direct pushes to `main`
- Minimum 1 reviewer
- CI must pass
- No secrets / tokens in code
- Descriptive PR title

## 🏷️ Labels

| Label | Use for |
|-------|---------|
| `bug` | Something broken |
| `feature` | New functionality |
| `task` | General work item |
| `blocked` | Waiting on something |