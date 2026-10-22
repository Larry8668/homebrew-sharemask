# homebrew-sharemask

Homebrew tap for [sharemask](https://github.com/Larry8668/share-mask) — share your screen without
sharing your chats (macOS 14+, Apple Silicon).

```sh
brew tap Larry8668/sharemask
brew install --cask --no-quarantine sharemask
```

`--no-quarantine` is needed because the app is signed with a self-signed certificate and not
notarised. On first launch grant Screen Recording in System Settings → Privacy & Security.
