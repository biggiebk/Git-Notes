---
layout: home
title: Searching
---

## Commands

### Bisect

See the [Working with Bisect](../how-to/working-with-bisect.md) page.

### Blame

```bash
git blame <fileName>
```

#### Blame on a specific Commit ID

```bash
git blame <commitID> <fileName>
```

### Command Reference Log

Run the following to view a log of all the git commands you have run in a repo.

```bash
git reflog
```

### Grep

Search the files that are tracked by the repo using a regex string.

```bash
git grep <searchString>
```

#### Case Insensitive

```bash
git grep -i <searchString>
```

#### Line Numbers

```
git grep -n <searchString>
```

#### Return Filename Only

```bash
git grep -l <searchString>
```

### Log

Remember these flags can be used with other ones to manipulate the view.

#### Diff Text Search

Search for text in files

```bash
git log -G <searchString> (fileName)
```

#### Commit Search

```bash
git log --grep <searchString
```

#### Pickax Search

Search the commit log

```bash
git log -S <searchString> (fileName)
```

#### Patch

Show the diff between each commit.

```bash
git log -p
```

#### Patch Word Diff

Patch with the word difference in line.

```bash
git log -p --word-diff
```
