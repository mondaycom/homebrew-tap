# monday.com Homebrew tap

Homebrew tap for monday.com's command-line tools.

## Install

```sh
brew install mondaycom/tap/mcli
```

## Contents

| Cask   | Description                                                               | Source                                              |
| ------ | ------------------------------------------------------------------------- | --------------------------------------------------- |
| `mcli` | Command-line interface for monday.com's GraphQL API, built for LLM agents | [mondaycom/mcli](https://github.com/mondaycom/mcli) |

Homebrew supports casks on macOS only. On Linux, install mcli with
[Nix](https://github.com/mondaycom/mcli#install), `go install`, or the release
tarballs.

## How this tap is maintained

Everything under `Casks/` is generated. Each `v*` tag in the source repository
runs GoReleaser, which builds the release artifacts and commits the updated cask
here. Do not edit those files by hand — the next release overwrites them.
