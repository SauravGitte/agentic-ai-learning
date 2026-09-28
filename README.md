# Agentic AI Learning

Personal repo for learning LangChain, LangGraph, MCP, and Agentic AI concepts.

## Folder Structure

```
Agentic_AI/
├── LangChain_Tutorial/
├── LangGraph/          # coming soon
├── MCP/                # coming soon
└── ...
```

Each subfolder is an independent UV project with its own virtual environment.

---

## Commands

### Starting a new topic folder

```bash
uv init --no-vcs        # init project WITHOUT creating a nested .git
uv venv                 # create virtual environment
.venv\Scripts\activate  # activate venv (Windows)
```

### Installing packages

```bash
uv add <package-name>   # add a dependency (updates pyproject.toml)
uv sync                 # reinstall all dependencies from pyproject.toml
```

### Pushing to GitHub

Run these from the root `Agentic_AI/` folder:

```bash
git add .
git commit -m "your message"
git push
```

---

> Git is configured locally with personal email — SAP global config is untouched.
