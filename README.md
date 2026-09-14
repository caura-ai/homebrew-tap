# Caura Homebrew tap

## Install

Homebrew requires you to trust third-party taps before it will load their
casks. For a first-time installation, run:

```sh
brew trust caura-ai/tap
brew tap caura-ai/tap
brew install --cask caura-ai/tap/caura
caura --version
```

To upgrade Caura later:

```sh
brew update
brew upgrade --cask caura-ai/tap/caura
```

Casks are auto-published by GoReleaser from the `caura-daemon` release workflow
on each stable release.
