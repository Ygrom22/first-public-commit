# Git Rebase Guide

## What Is Rebasing?
Rebasing reapplies commits onto a new base commit. It can create a linear project history.

## Basic Workflow

```bash
git switch docs/my-branch
git fetch origin
git rebase origin/main
```

Replace `docs/my-branch` with your actual branch name.

## Resolve Conflicts
1. Open each conflicted file.
2. Review the changes and resolve conflict markers.
3. Stage the resolved files:

```bash
git add <file>
git rebase --continue
```

Repeat until the rebase finishes.

## Cancel a Rebase

```bash
git rebase --abort
```

## Best Practices
- Commit your work before rebasing.
- Avoid rebasing shared branches.
- Remember that rebasing rewrites commit history.
- Review and test your changes afterward.
