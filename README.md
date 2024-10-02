ziglang mirror
==============

Mirror of ziglang for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit
For ziglang: see https://github.com/ziglang/zig-pypi

### Using ziglang with pre-commit:

Add this to your `.pre-commit-config.yaml`

```yaml
-   repo: https://github.com/elpekenin/mirrors-ziglang
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: zig_fmt
```
