# Karst & Sons Homebrew tap

```sh
brew install --cask karstandsons/tap/darkmatter
```

| Cask | What |
|---|---|
| `darkmatter` | [Darkmatter](https://github.com/karstandsons/darkmatter), an Omarchy-themed Mattermost client (universal: Apple Silicon and Intel) |

Updates arrive with `brew upgrade`. Casks here are updated automatically by
each project's release workflow.

Darkmatter isn't notarized by Apple yet, so the cask clears macOS's download
quarantine on install. Without it, macOS would refuse to open the app.
