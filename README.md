# Simple uv powered python package template

[![ci](https://github.com/pawamoy/copier-uv/workflows/ci/badge.svg)](https://github.com/pawamoy/copier-uv/actions?query=workflow%3Aci)
[![documentation](https://img.shields.io/badge/docs-mkdocs%20material-blue.svg?style=flat)](https://pawamoy.github.io/copier-uv/)
[![gitter](https://badges.gitter.im/join%20chat.svg)](https://app.gitter.im/#/room/#copier-uv/community:gitter.im)

[Copier](https://github.com/copier-org/copier) template
for Python projects managed by [uv](https://github.com/astral-sh/uv).

This copier template is mainly for my own usage,
but feel free to try it out, or fork it!

Similar templates:

- Original [copier-uv](https://github.com/pawamoy/copier-uv) project.
- [copier-pdm](https://github.com/pawamoy/copier-pdm), with [PDM](https://github.com/pdm-project/pdm)
- [copier-poetry](https:///github.com/pawamoy/copier-poetry), with [Poetry](https://github.com/python-poetry/poetry)

## Features

- [uv](https://github.com/astral-sh/uv) setup, with pre-defined `pyproject.toml`
- Pre-configured tools for code formatting, quality analysis and testing [ruff](https://github.com/astral-sh/ruff),
- Tests run with [pytest](https://github.com/pytest-dev/pytest) and plugins, with [coverage](https://github.com/nedbat/coveragepy) support
- Documentation built with [sphinx](https://github.com/sphinx-doc/sphinx) and [myst-parser](https://github.com/executablebooks/myst-parser)
- Support for GitHub workflows
- All licenses from [choosealicense.com](https://choosealicense.com/appendix/)

## Quick setup and usage

Start a new project with this template:

```bash
uvx --with=copier-template-extensions copier copy --trust "gh:mgaitan/copier-uv" /path/to/your/new/project
```

See the upstream project [documentation](https://pawamoy.github.io/copier-uv)
for more details.
