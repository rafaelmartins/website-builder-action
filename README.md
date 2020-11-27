# Website Builder action

This action builds a static website from sources using [rafaelmartins/website-builder](https://github.com/rafaelmartins/website-builder).

## Inputs

### `source-dir`

Source directory.

### `build-dir`

Build directory.

## Example usage

```yaml
uses: rafaelmartins/website-builder-action@master
with:
  source-dir: .
  build-dir: _build
```
