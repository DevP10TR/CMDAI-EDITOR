<div align="center">
  <img src="assets/banner.png" alt="CMDAI EDITOR" width="100%" />

  <p align="center">
    <a href="#"><img src="https://img.shields.io/badge/Python-3.10%2B-blue.svg?style=flat-square&logo=python" alt="Python 3.10+"></a>
    <a href="#"><img src="https://img.shields.io/badge/UI-Textual%20TUI-purple.svg?style=flat-square" alt="Textual TUI"></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square" alt="License: MIT"></a>
  </p>

### Terminal Code Editor & Diff Workspace for the CMDAI Ecosystem
*Tree-sitter syntax & diagnostics, Ruff linting, interactive diff view, integrated terminal, and multi-tab workspace.*

</div>

## 🌟 About

**CMDAI EDITOR** is a standalone Textual-based terminal code editor built for the **[CMDAI](https://github.com/DevP10TR/CMDAI)** and **[CMDAI CODE](https://github.com/DevP10TR/CMDAI-CODE)** ecosystem:
- **Tree-sitter Syntax & Diagnostics**: Built-in AST syntax highlighting and live error checking across Python, JavaScript, HTML, CSS, Go, Rust, Bash, JSON, TOML, and YAML.
- **Ruff Linter & Problems Pane**: Real-time diagnostics panel (`PROBLEMS`) combining Tree-sitter syntax checks with `ruff` lint rules.
- **Interactive Diff Mode (`--diff` / `-d`)**: Side-by-side / inline diff inspection for reviewing code changes made by you or **CMDAI CODE**.
- **Integrated Terminal, Search & Explorer**: File tree explorer, quick-open file switcher, project-wide search, multi-tab code buffers, and embedded runner/terminal.

---

## 🚀 Key Features

- 🌳 **10 Tree-sitter Grammars**: Fast, accurate highlighting and structural syntax checks without heavy language servers.
- 🔍 **Quick Open & Global Search**: Instant file navigation and project-wide text search (`core/search.py`, `ui/quick_open.py`).
- 🐛 **Live Problems Panel**: Aggregates Tree-sitter syntax errors and `ruff` diagnostics in one place.
- 🔀 **Diff Viewer (`--diff`)**: Dedicated diff mode (`run.bat <path> --diff` or `python main.py <path> --diff`) for reviewing edits cleanly in the terminal.
- 🎨 **Custom Icon Font (`icons/cmdai-icons.ttf`)**: Bundled glyph font and generator scripts (`icons/build_font.py`, `icons/install_font.py`) for crisp file-tree icons.

---

## 📥 Installation & Usage

### 1. Git Clone & Setup
```bash
git clone https://github.com/DevP10TR/CMDAI-EDITOR.git
cd CMDAI-EDITOR
.\install.bat
```

Or install manually with `pip`:
```bash
pip install -r requirements-editor.txt
```

### 2. Launch
```bash
# Open a folder or launch the project picker
.\run.bat [target_directory]

# Or run directly with Python
python main.py [target_directory]

# Launch directly in Diff View
python main.py [target_directory] --diff
```

---

## 🔗 Ecosystem

- **[CMDAI](https://github.com/DevP10TR/CMDAI)** — Autonomous local AI runtime & CMDAI CODE controller
- **[CMDAI CODE](https://github.com/DevP10TR/CMDAI-CODE)** — Autonomous terminal coding agent
- **[LocalLLMAPI](https://github.com/DevP10TR/LocalLLMAPI)** — Dedicated local LLM router & server

---

## 📄 License

Licensed under the **MIT License** — anyone is free to use, modify, and distribute this software. See [LICENSE](LICENSE) for details.
