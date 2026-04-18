# Homebrew Tap — Tally

Homebrew formula for [Tally](https://github.com/suannai231/tally-releases), the team-owned quality gate that blocks commits and CI on AI-generated code violations.

## Install

```bash
brew install suannai231/tap/tally
```

## Upgrade

```bash
brew update
brew upgrade tally
```

## What's in this repo

- `tally.rb` — the Homebrew formula. Auto-updated by [GoReleaser](https://goreleaser.com) on every `v*` tag pushed to the Tally source repo.

No manual commits land here. If the formula drifts from the latest release, something went wrong in the release pipeline — check [`tally-releases`](https://github.com/suannai231/tally-releases) for the canonical artifacts.

## See also

- [`suannai231/tally-releases`](https://github.com/suannai231/tally-releases) — product description, release binaries, and release notes
- [`suannai231/tally-action`](https://github.com/suannai231/tally-action) — GitHub Action for CI enforcement
