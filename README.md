# pre-commit hooks for fish scripts

[pre-commit](https://pre-commit.com/) hook that validates fish syntax and automatically format files

Usage

```yaml
repos:
  - repo: https://github.com/yujinyuz/pre-commit-fish.git
    rev: v0.1.0
    hooks:
      - id: fish_syntax
      - id: fish_format
```
