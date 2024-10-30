# BingoMaker

## Development

### Setup

Please install the following

* [uv](https://docs.astral.sh/uv/#getting-started) for project management

```bash
git clone https://github.com/cs399f24/BingoMaker
cd BingoMaker
uv sync
```

### Testing

To run tests for the project you can either run `uvx pytest` or activate the virtual environment and run `pytest`

### Linting/Formatting

[Ruff](https://docs.astral.sh/ruff/) is used to lint and format the project.

Linting can be done in the following ways

```bash
make lint
uvx ruff check
uv tool run ruff check
.venv/bin/ruff check
```

Formatting can be done similarly

```bash
make format
uvx ruff format
uv tool run ruff check
.venv/bin/ruff format
```