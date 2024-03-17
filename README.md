# Minimal examples

## Backends

- flit
- hatchling
- pdm
- setuptools

While setuptools and flit are working with tox-uv, hatchling and pdm have issues
with a `package = editable`.

Please check <https://github.com/tox-dev/tox-uv/issues/41> for details.

## Reproduce

```bash
pip install tox-uv
cd minimal-hatch
tox
```
