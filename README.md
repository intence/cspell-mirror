# Mirror for cspell
Mirroring [cspell](https://www.npmjs.com/package/cspell).

Built to be deployed with [pre-commit](https://pre-commit.com/).

## Usage
Add this entry in your `.pre-commit-config`.
```
repos:
  ...
  - repo: git://github.com/intence/cspell-mirror.git
    rev: 1.0.0
    hooks:
      - id: cspell
  ...
```
