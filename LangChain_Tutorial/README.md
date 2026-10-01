# Readme File

## Project Setup

The following commands were used to initialize and set up the Python environment using **uv**.

### 1. Initialize the Project

```bash
uv init --no-vcs          # init WITHOUT creating a nested .git
```

Initializes the project and creates the required `uv` configuration files.

### 2. Create a Virtual Environment

```bash
uv venv
```

Creates a Python virtual environment in the `.venv` directory.

### 3. Activate the Virtual Environment

**Windows:**

```powershell
.venv\Scripts\activate
```

Activates the newly created virtual environment.

### 4. Add requirements

**Windows:**

```powershell
uv add -r requirements.txt
```
