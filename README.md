# ⚡️ Viswa‑JS‑Interpreter

[![GitHub Repo](https://img.shields.io/badge/GitHub-Viswa%2FCodes/js--interpreter-blue?logo=github)](https://github.com/Viswa-Codes/js-interpreter)
[![PyPI Version](https://img.shields.io/pypi/v/viswa-js-interpreter.svg?v=0.1.1)](https://pypi.org/project/viswa-js-interpreter/0.1.1/)

A **custom JavaScript runtime written in pure Python**.  
It tokenises, parses (Pratt parser), builds an AST and evaluates JavaScript code with proper scoping, closures, built‑in objects (`Math`, `Date`, arrays, etc.) and many language features.

--- 

## 📦 Installation  

```bash
pip install viswa-js-interpreter
```
---
## 🚀 Development Setup

Clone the repository:

```bash
git clone https://github.com/Viswa-Codes/js-interpreter.git
cd js-interpreter
```

Create and activate a virtual environment:

### Windows (PowerShell)

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

### Linux / macOS

```bash
python -m venv .venv
source .venv/bin/activate
```

Install development dependencies:

```bash
pip install -U pip build twine
```

Run the interpreter locally:

```bash
python -m js_runtime.js_run examples/test.js
```

---

## 🤝 Contributing

1. Fork the repository.
2. Create a new branch:

```bash
git checkout -b feature/my-feature
```

3. Make your changes.
4. Commit your changes:

```bash
git commit -m "Add: my feature"
```

5. Push your branch:

```bash
git push origin feature/my-feature
```

6. Open a Pull Request against the `main` branch.

Please ensure:

* Existing functionality continues to work.
* New features include tests when possible.
* Code follows the project's style.
* Documentation is updated if needed.

---

## 🐛 Reporting Issues

If you find a bug or have a feature request, please open a GitHub Issue with:

* Steps to reproduce
* Expected behavior
* Actual behavior
* Python version
* Operating system

