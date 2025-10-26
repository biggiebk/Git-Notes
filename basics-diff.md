---
layout: home
title: Diff
---

## Commands

### Branches

```bash
git diff <branchName1> <brancheName2> --
```

### Commits

```bash
git diff <commitId1> <commitId2> --
```

### General Options

#### By word not line

```bash
git diff --word-diff --
```

### Index and the object database

```bash
git diff --cached --
```

#### File in index and the object database

```bash
git diff --cached -- <fileName>
```

### Working directory and index

```bash
git diff --
```

#### File and that file in index

```bash
git diff -- <fileName>
```
