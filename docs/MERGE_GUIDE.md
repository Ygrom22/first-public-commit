# Git Merge Guide

## What Is Merging?
Merging combines changes from one branch into another branch.

## Before Merging
- Check the current branch.
- Review the changes.
- Make sure your work is committed.
- Update the target branch when appropriate.

## Merge a Branch
Switch to the branch that should receive the changes:

```bash
git switch main
git merge docs/update-readme
```

Replace docs/update-readme with the actual branch name.

## Resolve Merge Conflicts
1. Open each file marked as conflicted.
2. Review both versions of the changes.
3. Edit the file to keep the intended result.
4. Remove conflict markers.
5. Test and review the resolved file.
6. Stage the resolved files and complete the merge.

## Check the Result

```bash
git status
git log --oneline --graph
```

## Best Practices
- Understand both sides before resolving conflicts.
- Avoid overwriting changes without reviewing them.
- Test the result after merging.
- Use a pull request when review is needed.

Merging should preserve the intended changes from both branches.
