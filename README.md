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

## First-Time Setup (New Machine)

### 1. Install UV (only missing tool)

Git, Python, VS Code are assumed installed. UV is the only extra:

```bash
pip install uv
```

### 2. Clone the repo

```bash
git clone https://github.com/SauravGitte/agentic-ai-learning.git
cd agentic-ai-learning
```

### 3. Set local git config

```bash
git config user.email "your@email.com"
git config user.name "Your Name"
```

> Do this once per machine so commits go to the right account.

### 4. Set up a subfolder

```bash
cd LangChain_Tutorial
uv venv
.venv\Scripts\activate    # Windows
uv sync                   # installs all dependencies from pyproject.toml
```

---

## Daily Commands

### Starting a new topic folder

```bash
uv init --no-vcs          # init WITHOUT creating a nested .git
uv venv
.venv\Scripts\activate
```

### Installing packages

```bash
uv add <package-name>     # adds dependency, updates pyproject.toml
uv sync                   # reinstall all deps from pyproject.toml
```

### Pushing to GitHub

Run from the root `agentic-ai-learning/` folder:

```bash
git add .
git commit -m "your message"
git push
```
