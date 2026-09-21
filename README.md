# Caura Homebrew tap

> **This tap is retired. 0.11.0 is its final release.**
>
> Automated publishing was removed from the `caura-daemon` release workflow on
> 2026-09-09, so no version after 0.11.0 will appear here. 0.11.0 was pinned
> manually so that anyone already installed gets one last upgrade — it is the
> first release whose artifacts and binary carry the `caura` name.
>
> Move to a supported channel when convenient:
>
> ```sh
> curl -fsSL https://caura.ai/install.sh | sh
> ```
>
> or `npx caurad` / `uvx caurad`. See <https://caura.ai> for the current
> install guide.

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

Casks were auto-published by GoReleaser from the `caura-daemon` release
workflow until 2026-09-09, when that configuration was removed. The 0.11.0 cask
was written by hand as the final release; nothing regenerates it.
