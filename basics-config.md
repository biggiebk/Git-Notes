---
layout: home
title: Config
---

## Commands

### Alias

```bash
git config (--global) alias.<aliasName> "<command> (arg1) (arg2) (...)"
```

### List

```bash
git config -l
```

#### With Origins

```bash
git config -l --show-origin
```

### Unset

```bash
git config (--global) --unset <keyName>
```

### Update

```bash
git config --global <key> <value>
```
