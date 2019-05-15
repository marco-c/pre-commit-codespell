isort mirror
============

Mirror of codespell package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For isort: see https://github.com/codespell-project/codespell


### Using codespell with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
-   repo: https://github.com/marco-c/mirrors-codespell
    rev: ''  # Use the revision sha / tag you want to point at
    hooks:
    -   id: codespell
```
