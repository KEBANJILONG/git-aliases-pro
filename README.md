# ⚡ Git Aliases Pro

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Platform](https://img.shields.io/badge/platform-All-lightgrey.svg)

**Supercharge your Git workflow with 100+ curated aliases**

</div>

## 🚀 Quick Start

```bash
# One-line installercurl -fsSL https://raw.githubusercontent.com/KEBANJILONG/git-aliases-pro/main/install.sh | bash
```

## ✨ Features

- **100+ aliases** - From basic to advanced
- **Cross-platform** - Works on macOS, Linux, WSL
- **Categories** - Status, branching, commits, history, remote
- **Safe** - Never overrides your existing aliases

## 📋 Alias Categories

### Status & Info
```bash
gst      # git status -sb
gl       # git log --oneline --graph -10
gd       # git diff
gds      # git diff --staged
```

### Branching
```bash
gb       # git branch -agco      # git checkout
gcb      # git checkout -b
gbd      # git branch -d
gbD      # git branch -D
```

### Commits
```bash
gc       # git commit
gcm      # git commit -m
gca      # git commit --amend
gcan     # git commit --amend --no-edit
```

### Remote
```bash
gp       # git push
gpf      # git push --force-with-lease
gpl      # git pull
gf       # git fetch --all
```

## 🔧 Manual Install

```bash
git clone https://github.com/KEBANJILONG/git-aliases-pro.git
cd git-aliases-pro
./install.sh
```

## 📄 License

MIT
