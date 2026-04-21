# filippolmt/homebrew-tap

Homebrew tap for [`toolbox`](https://github.com/filippolmt/toolbox) — a CLI that
drops you into a disposable, reproducible containerised dev environment bundling
Claude Code, cloud CLIs, Node, Python, Docker, kubectl, and more.

## Install

```sh
brew install filippolmt/tap/toolbox
```

Or add the tap first:

```sh
brew tap filippolmt/tap
brew install toolbox
```

## Upgrade

```sh
brew upgrade filippolmt/tap/toolbox
```

## Notes

- The formula is auto-generated on every tagged release by
  [GoReleaser](https://github.com/filippolmt/toolbox/blob/main/.goreleaser.yaml).
- Supported platforms: macOS (Intel/ARM) and Linux (amd64/arm64).
- Do not edit `Formula/toolbox.rb` manually — changes are overwritten on the
  next release.
