---
layout: home
title: Branch
---

## Commands

### Create

```bash
git branch <branchName>
```

#### Create and Switch in One

```bash
git switch -c <branchName>
```

#### Create Branch from Specific Commit ID

```bash
git branch <branchName> <commitID>
```

### Delete

Local

```bash
git branch -d <branchName>
```

#### Force Delete Local

```bash
git branch -D <branchName>
```

#### Remote Delete

```bash
git push -d origin <branchName>
```

### Fetch

Retrieves all remote branches without updating any local branches

If you want to have the remote branch on the local one you need to merge after the fetch.

```bash
git fetch
```

#### Prune remotes that no longer exist

```bash
git fetch -p
```

### Pull

```bash
git pull
```

### List

A \* denotes the current branch

```bash
git branch
```

### Push

#### Remote Already Set

```bash
git push
```

#### Specify Remote

```bash
git push -u origin <branchName>
```

### Rename

#### Current Branch

```bash
git branch -m <newBranchName>
```

#### Specify  Branch

```bash
git branch -m <oldBranchName> <newBranchName>
```

### Switch

```bash
git switch <branchName
```
