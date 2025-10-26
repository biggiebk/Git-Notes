---
layout: home
title: File/Folder Tracking
---

## Commands

### Add

#### All

```bash
git add -A
```

#### Specific Files

```bash
git add <fileORfolder1> <fileORfolder2> ...
```

### Delete

#### File

```bash
git rm <fileName1> <fileName2>
```

#### Folder

```bash
git rm -r <folderName1>
```

#### If you did non git rm/delete

```bash
git add -u <fileName1> <fileName2>
```

#### From index

```bash
git rm --cached <fileORfolder1>
```

### Rename

```bash
git mv -u <oldFileName> <newFileName>
```

### Restore

#### Index to working dir

```bash
git restore <fileORfolder1> <fileORfolder2> ...
```

#### Object DB to the index

```bash
git restore --staged <fileORfolder1> <fileORfolder2> ...
```

#### Specific from a specific commit

```bash
git restore --source <commitID> <fileName>
```
