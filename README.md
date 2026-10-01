# loha

A next-gen application server for Python.

Loha is in early development. This initial package supports importing and
checking its version; server functionality is not implemented yet.

## Installation

Once published on PyPI:

```sh
python -m pip install --pre loha
```

For local development:

```sh
python -m pip install -e .
```

## Usage

```python
import loha

print(loha.__version__)
```

## Publishing

Build the wheel and source distribution with `uv build`, then upload with
`uv publish`. Publishing requires PyPI authentication, such as a token supplied
through the `UV_PUBLISH_TOKEN` environment variable.
