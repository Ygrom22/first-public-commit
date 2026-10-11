# Git Stash Guide

## What Is Git Stash?
Git stash temporarily saves uncommitted changes so you can work on something else without creating a commit.

## Save Changes

```bash
git stash push -m "work in progress"
```

## List Stashes

```bash
git stash list
```

## Restore Changes
Apply the latest stash and keep it in the stash list:

```bash
git stash apply
```

Apply the latest stash and remove it from the stash list:

```bash
git stash pop
```

## Remove a Stash

```bash
git stash drop stash@{0}
```

Review the stash list before removing an entry.

## Best Practices
- Add a message when saving important work.
- Check `git status` before and after stashing.
- Remember that untracked files are not included by default; use `git stash -u` when needed.
- Verify restored changes before committing.
