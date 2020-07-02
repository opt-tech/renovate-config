# @opt-tech/renovate-config

[Shareable config](https://renovatebot.com/docs/config-presets/) for [Renovate](https://renovatebot.com/)

## Usage

```json
{
  "extends": ["github>opt-tech/renovate-config"]
}
```

## Concepts

- prefer pin for npm
- automerge patch for all deps
- automerge minor
  - dev deps and
  - circleci orbs
- rebase stale prs
- maintain lock files weekly
- [SemVer stability score](https://dependabot.com/compatibility-score.html/) badge from [Dependabot](https://dependabot.com/)

The renovate config presets are stored in [renovate.json](renovate.json).
