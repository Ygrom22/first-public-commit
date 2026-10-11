# Git Branching Guide

## What Is a Branch?
A branch lets you work on changes separately from the main line of development.

## Create a Branch
Use a short, descriptive name for the task.

```bash
git switch -c docs/update-readme
```

## Check Your Current Branch

```bash
git branch --show-current
```

## Review Your Changes

```bash
git status
git diff
```

## Commit Changes

```bash
git add README.md
git commit -m "docs: update readme"
```

Replace README.md with the file you actually changed.

## Push Your Branch

```bash
git push -u origin docs/update-readme
```

## Open a Pull Request
On GitHub, compare your branch with the main branch and open a pull request when the changes are ready.

## Best Practices
- Keep branches focused on one task.
- Use descriptive branch names.
- Review the diff before committing.
- Avoid committing secrets or unrelated changes.
- Delete merged branches when they are no longer needed.

Commands may need adjustment for the specific repository and workflow.
