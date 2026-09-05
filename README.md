# enVolt Homebrew Tap

Official Homebrew tap for [enVolt](https://github.com/enVolt) macOS tools.

## Installation

### yaxbar (maintained xbar fork)

```bash
brew install --cask envolt/tap/yaxbar
```

Or manually tap first:

```bash
brew tap envolt/tap
brew install --cask yaxbar
```

### Gatekeeper Note

Because \`yaxbar\` is open source and ad-hoc signed, on first launch macOS may show a developer verification prompt. If so, simply right-click (Control-click) \`yaxbar.app\` -> **Open**, or run:

```bash
xattr -cr /Applications/yaxbar.app
```

---

## Updating

```bash
brew upgrade --cask yaxbar
```
