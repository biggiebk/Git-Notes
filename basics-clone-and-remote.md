---
layout: home
title: Clone and Remote
---

## Commands

### Clone

```bash
git clone <urlToRemote>
```

Clone under a different folder

```bash
git clone <urlToRemote> <diffFolderName>
```

### Push

```bash
git push
```

### Remote

Displays information on which remote is used for fetch and push

#### Basic

```bash
git remote
```

#### Detailed

```bash
git remove -v
```

### Tag

Create

```bash
git tag <name> (commitID or branchName) # Name should likely be a version v#.#.#
```

List Tags

```bash
git tag --list
```
