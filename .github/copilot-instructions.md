# GitHub Copilot Instructions

## Mandatory Development Checklist

- [ ] Run linting: `uv run ruff check .`
- [ ] Build the app: `uv run uvicorn app.main:app --reload --host 0.0.0.0 --port 8000`
- [ ] Run tests: `uv run pytest`

## Quick Commands

- **Run the app**: `uv run uvicorn app.main:app --reload`
- **Run tests**: `uv run pytest`
- **Run linting**: `uv run ruff check .`
- **Sync dependencies**: `uv sync`

## Overview

- **`app/`**: FastAPI routes, game logic, templates.
- **`templates/`**: Jinja2 templates for HTML.
- **`tests/`**: `pytest` test suite.
- **`static/`**: CSS and JavaScript.

## Conventions

- Python 3.13+, FastAPI, Jinja2, HTMX.
- Follow PEP 8; use `ruff` for linting.

## Pitfalls

- **Browser Preview**: Use an external browser, not VS Code's Simple Browser.
- **Edge Dependency**: Install Microsoft Edge for Playwright tools.

## Links

- [CONTRIBUTING.md](../CONTRIBUTING.md): Contribution guidelines.
- [README.md](../README.md): Project overview.
- [Workshop Guide](../workshop/GUIDE.md): Workshop instructions.

## Example Prompts

- "Run the app and verify it works."
- "Add a new FastAPI route."
- "Create a Jinja2 template for the game screen."