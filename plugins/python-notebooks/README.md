# Python notebooks

Create and edit clean Jupyter notebooks, write marimo reactive notebooks or convert Jupyter ones to marimo, and work in a running Jupyter server through the Jupyter MCP server.

Reviewed before publishing. Details, files and install options for every tool: https://playbookrun.com/p/python-notebooks

## Install

Claude Code:

```
/plugin marketplace add Fcakiroglu16/marketplace
/plugin install python-notebooks@playbookrun
```

Codex:

```
codex plugin marketplace add Fcakiroglu16/marketplace
codex plugin add python-notebooks@playbookrun
```

Cursor: a team admin imports https://github.com/Fcakiroglu16/marketplace as a team marketplace.

Notebooks that stay readable: scaffold and edit `.ipynb` experiments and tutorials, write marimo notebooks in the right format, and convert Jupyter notebooks to marimo `.py` files. The Jupyter MCP server edits and runs cells in a Jupyter server you start yourself; set `JUPYTER_URL` and `JUPYTER_TOKEN`.

## Skills

- `jupyter-notebook`: Use when the user asks to create, scaffold, or edit Jupyter notebooks (`.ipynb`) for experiments, explorations, or tutorials; prefer the bundled templates and r…
- `marimo-notebook`: Write a marimo notebook in a Python file in the right format.
- `jupyter-to-marimo`: Convert a Jupyter notebook (.ipynb) to a marimo notebook (.py).

## MCP servers

- **Jupyter**: Datalayer's Jupyter MCP server: open notebooks, insert, edit and run cells and read outputs in a running Jupyter server. Needs uv, JUPYTER_URL and JUPYTER_TOKEN.

All skills are copied unchanged from [openai/skills](https://github.com/openai/skills) under Apache 2.0 and [marimo-team/skills](https://github.com/marimo-team/skills) under Apache 2.0; each skill folder includes its licence and `SOURCE.md` with the source commit.
