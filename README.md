# pre-commit-alejandra

alejandra for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit
For alejandra: see https://github.com/kamadorueda/alejandra

## Using alejandra with pre-commit

Add this to your `.pre-commit-config.yaml`

```yaml
  - repo: https://github.com/34j/pre-commit-alejandra
    rev: "" # The the revision or tag you want to use
    hooks:
      - id: alejandra
```
