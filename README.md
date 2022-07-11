# Setup age

This action sets up [age](https://github.com/FiloSottile/age) and adds it to the PATH.

## Usage

Basic:

```yaml
steps:
  - uses: adnsio/setup-age-action@v1.2.0
  - run: age --version
```

Specific version:

```yaml
steps:
  - uses: adnsio/setup-age-action@v1.2.0
    with:
      version: ^1.0.0
  - run: age --version
```
