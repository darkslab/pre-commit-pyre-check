# pyre-check pre-commit hook

[pre-commit](https://pre-commit.com) hook for
[pyre-check](https://github.com/facebook/pyre-check).

## Using pyre-check with pre-commit

Add this to your `.pre-commit-config.yaml`

```yaml
- repo: https://github.com/darkslab/pre-commit-pyre-check
  rev: 'v1-0.9.10' # pre-commit-pyre-check (v1) and pyre-check (0.9.10)
  hooks:
    - id: pyre-check
```
