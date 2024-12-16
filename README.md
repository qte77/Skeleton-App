# <project_name>

<project_description>

![version](https://img.shields.io/badge/version-0.0.0-8A2BE2)
[![CodeFactor](https://www.codefactor.io/repository/github/qte77/__REPO_NAME__/badge)](https://www.codefactor.io/repository/github/qte77/__REPO_NAME__)
[![Ruff](https://github.com/qte77/__REPO_NAME__/actions/workflows/ruff.yml/badge.svg)](https://github.com/qte77/__REPO_NAME__/actions/workflows/ruff.yml)
[![Links (Fail Fast)](https://github.com/qte77/__REPO_NAME__/actions/workflows/links-fail-fast.yml/badge.svg)](https://github.com/qte77/__REPO_NAME__/actions/workflows/links-fail-fast.yml)
![semver](https://img.shields.io/badge/semver-2.0.0-blue)
[![Open in Visual Studio Code](https://img.shields.io/static/v1?logo=visualstudiocode&label=&message=Open%20in%20Visual%20Studio%20Code&labelColor=2c2c32&color=007acc&logoColor=007acc)](https://vscode.dev/github/qte77/__REPO_NAME__)

## Status

(DRAFT) (WIP) ----> Not fully implemented yet

For version history have a look at the [CHANGELOG](CHANGELOG.md).

## Setup

1. **Install Dependencies**:

- `uv install`

2. **Run the Application**:

- **CLI Mode**: `uv run app/main.py --cli`

## Usage

- **CLI**: Use the CLI to query models directly from the command line.

## Testing

Run tests using: `pytest tests/`

## Documentation

- **Project DSL**: See `[docs/project_dsl.txt](docs/project_dsl.txt)` for a high-level overview of the project structure and functionality.
- **PRD**: See `[docs/PRD.md](docs/PRD.md)` for detailed product requirements.

### Architecture

<img src="assets/c4-arch.dark.png#gh-dark-mode-only" alt="C4-Arch" title="C4-Arch" width="60%" /> <!-- mkdocs exclude { data-search-exclude } -->
<img src="assets/c4-arch.light.png#gh-light-mode-only" alt="C4-Arch" title="C4-Arch" width="60%" />

## Project Structure

```sh
/
├─ app/
│  ├─ __init__.py
│  ├─ __main__.py
│  └─ __version__.py
├─ tests/
├─ docs/
│  ├─ project_dsl.txt
│  ├─ PRD.md
│  └─ architecture/
│     └─ c4_diagram.md
├─ Dockerfile
├─ README.md
└─ pyproject.toml
```
## TODO

