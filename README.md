# Simple uv powered Python package template

> Inspired by [pawamoy/copier-uv](https://github.com/pawamoy/copier-uv), but with fewer options and a simpler configuration.

A [Copier](https://github.com/copier-org/copier) template
for Python projects managed by [uv](https://github.com/astral-sh/uv).


## Features

- [uv](https://github.com/astral-sh/uv) setup, with pre-defined `pyproject.toml`
- Pre-configured tools for code formatting, quality analysis and testing [ruff](https://github.com/astral-sh/ruff),
- Tests run with [pytest](https://github.com/pytest-dev/pytest) and plugins, with [coverage](https://github.com/nedbat/coveragepy) support
- Documentation built with [sphinx](https://github.com/sphinx-doc/sphinx) and [myst-parser](https://github.com/executablebooks/myst-parser)
- Support for GitHub workflows
- Only the most common permissive licenses (BSD-3-Clause, MIT, Apache-2.0)

## Quick setup and usage

Start a new project with this template:

```bash
uvx --with=copier-template-extensions copier copy --trust "gh:mgaitan/copier-uv" /path/to/your/new/project
```

To upgrade an existing project created from this template to the latest version, run:

```bash
copier update .
```

This will fetch the latest template version and guide you through updating your project, preserving your customizations whenever possible.

To test a development version of the template, clone the repository and run:

```bash
uv sync
uv run copier copy --trust  --vcs-ref=HEAD . /path/to/your/test/project
```
