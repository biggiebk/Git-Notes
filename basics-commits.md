---
layout: home
title: Commits
---

## Commands

### Commit Changes

```bash
git commit -m "Your brief message here"
```

### Update Last Commit Message

Make sure there are no fresh updates pending. When updating the last commit message any new changes will be committed along with other changes. This only works on the last commit.

git commit --amend -m "New commit message"

### Log History

Verbose log of current branch

```bash
git log
```

Compact log of current branch

```bash
git log --oneline
```

Log of all commits in the repository displayed as graph

```bash
git log --oneline --all --graph
```

### Reset

Used to reset to a previous commit. See [understanding resets ](howto-undoing-commits-reset.html)for more details on the different types.

#### Hard

```bash
git reset --hard <commitID>
```

#### Mixed (Default)

```
git reset <commitID>
```

#### Soft

```bash
git reset --soft <commitID>
```

### Revert

Similar to reset, however only has one mode and instead of deleting commits this one undoes the changes and then makes a new commit.

```bash
git revert <commitID>
```

### Specific Commit

Will put the repo into headless state

```bash
git checkout <commitID>
```
