# Modern Python and FastAPI

Astral's official uv, Ruff and ty skills, FastAPI's own skill shipped in the FastAPI repository and Pydantic's official skill.

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install python-fastapi@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add python-fastapi@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Python tooling and APIs from the people who build them: uv for projects, dependencies and Python versions, Ruff for linting and formatting, ty for type checking, FastAPI's conventions for dependencies, models and streaming, and Pydantic's modelling rules. FastAPI's skill mentions FastAPI Cloud as one deploy option; any deploy goes to your account, so the agent should ask first.

## Skills

- `uv`: Guide for using uv, the Python package and project manager. Use this when working with Python projects, scripts, packages, or tools.
- `ruff`: Guide for using ruff, the extremely fast Python linter and formatter. Use this when linting, formatting, or fixing Python code.
- `ty`: Guide for using ty, the extremely fast Python type checker and language server. Use this when type checking Python code or setting up type checking in Python pr…
- `fastapi`: FastAPI best practices and conventions. Use when working with FastAPI APIs, Pydantic models, dependencies, streaming responses including Server-Sent Events (SSE…
- `pydantic`: Pydantic is a Python data validation and serialization library, based on type hints. Use this skill whenever you need to do relatively complex data modeling usi…

## MCP servers

- **Context7**: Upstash's Context7 MCP server: current, version-specific documentation and code examples for thousands of libraries. Works without a key; set CONTEXT7_API_KEY for higher rate limits.

All skills are copied unchanged from [astral-sh/agent-plugins](https://github.com/astral-sh/agent-plugins) under the MIT, [fastapi/fastapi](https://github.com/fastapi/fastapi) under the MIT and [pydantic/skills](https://github.com/pydantic/skills) under the MIT; each skill folder includes its licence and `SOURCE.md` with the source commit.
