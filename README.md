# filippolmt/homebrew-tap

Homebrew tap for [@filippolmt](https://github.com/filippolmt)'s tools. Each
release of a supported project publishes a Homebrew cask here automatically, so
you can install and upgrade everything through `brew`.

## Available casks

| Cask | Description | Source |
| --- | --- | --- |
| `toolbox` | CLI that drops you into a disposable, reproducible containerised dev environment (Claude Code, cloud CLIs, Node, Python, Docker, kubectl, and more). | [filippolmt/toolbox](https://github.com/filippolmt/toolbox) |
| `proximo` | Local development reverse proxy with automatic DNS and trusted HTTPS. | [filippolmt/proximo](https://github.com/filippolmt/proximo) |

## Install

Add the tap once:

```sh
brew tap filippolmt/tap
```

Then install any cask:

```sh
brew install --cask toolbox
brew install --cask proximo
```

Or install without tapping first:

```sh
brew install --cask filippolmt/tap/toolbox
brew install --cask filippolmt/tap/proximo
```

## Upgrade

```sh
brew upgrade --cask toolbox
brew upgrade --cask proximo
```

## Notes

- Supported platforms: macOS (Intel/ARM) and Linux (amd64/arm64).
- Each cask is auto-generated on every tagged release by
  [GoReleaser](https://goreleaser.com/) in its source repository.
- Do not edit files in `Casks/` manually — they are overwritten on the next
  release of the corresponding project.
