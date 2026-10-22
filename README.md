# homebrew-sharemask

Homebrew tap for [sharemask](https://github.com/Larry8668/share-mask) — share your screen without
sharing your chats (macOS 14+, Apple Silicon).

```sh
brew tap Larry8668/sharemask
brew trust Larry8668/sharemask     # Homebrew 7+: third-party taps must be trusted
brew install --cask sharemask
```

The app is signed with a self-signed certificate and not notarised; the cask removes the
quarantine attribute after install so it opens normally. On first launch grant Screen Recording in
System Settings → Privacy & Security.
