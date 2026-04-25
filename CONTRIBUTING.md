# Contributing to FinAI

## Branch Strategy

We follow a simple Git Flow:

```
main          ← stable, production-ready code only
dev           ← active development branch (merge here first)
feature/xxx   ← individual feature branches
fix/xxx       ← bug fix branches
```

## Workflow

### 1. Always branch off `dev`
```bash
git checkout dev
git pull origin dev
git checkout -b feature/your-feature-name
```

### 2. Commit conventions
Use clear, descriptive commit messages:
```
feat: add CSV upload parser
fix: resolve session timeout bug
docs: update README setup steps
refactor: clean EDA pipeline logic
```

### 3. Push and open a Pull Request
```bash
git push origin feature/your-feature-name
```
Then open a Pull Request → `dev`. Tag at least one teammate for review.

### 4. Never push directly to `main`
`main` is updated only via PR from `dev` after team review.

---

## Folder Ownership

| Folder | Owner(s) |
|---|---|
| `src/tools/` | Bader, Abdulrahman A., Abdulrahman H. |
| `src/ui/` | Faris |
| `src/database/` | Yazeed |
| `docs/` | All |
| `tests/` | All |
