# CONTRIBUTING.md

Welcome to the **DSc AI Research Division**!  
This guide will help you get from zero to your first merged pull request in a few clear steps.

---

## 1. Code of Conduct
By participating, you agree to uphold our simple rules:

- Be respectful and inclusive.  
- Focus on constructive feedback.  
- Keep discussions on-topic (AI, data science, software).  

---

## 2. Quick Start

| Step | Command / Action |
|------|------------------|
| 1. Fork | Click **Fork** (top-right of this repo). |
| 2. Clone | `git clone https://github.com/<YOUR-USERNAME>/dsc-ai-research.git` |
| 3. Branch | `git checkout -b feature/your-topic` |
| 4. Code | Follow the style guides below. |
| 5. Commit | `git commit -m "feat: add attention heat-map util"` |
| 6. Push | `git push origin feature/your-topic` |
| 7. PR | Open a Pull Request against `main`. |

---

## 3. Branch Naming
- `feature/<short-description>` – new functionality  
- `fix/<short-description>` – bug fixes  
- `docs/<short-description>` – documentation only  
- `research/<paper-or-experiment>` – experimental code or notebooks  

---

## 4. Commit Messages
Use **Conventional Commits** for clarity:
<type><scope><subject>
<body> (optional)
Closes #<issue-number>


**Types:** `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`.  
**Examples:**  
- `feat(models): add Vision Transformer baseline`  
- `docs(readme): update Discord invite link`  

---

## 5. Style Guides

### Python
- **Formatter:** `black` (88 chars)  
- **Linter:** `ruff` (or `flake8`)  
- **Type hints:** encouraged (`mypy --strict`)  

### Notebooks
- Clear section headers (`# 1. Data`, `# 2. Model`, …)  
- Restart & run-all before committing.  
- Commit `.ipynb` *and* an exported `.py` if the notebook is large.

### Markdown / Docs
- 100-char soft wrap.  
- Use **ATX-style** headings (`#`, `##`).  

---

## 6. Folder Layout

├── notebooks/          # Exploratory work
├── src/
│   ├── models/         # Model definitions
│   ├── data/           # Data loaders / utils
│   └── eval/           # Evaluation scripts
├── experiments/        # Reproducible scripts (Hydra / YAML configs)
├── docs/               # Markdown docs & figures
└── tests/              # pytest unit tests

---

## 7. Pull Request Template
Copy-paste into your PR description:

## What
Brief description of the change.

## Why
Link to issue or motivation.

## How to test
1. `pip install -r requirements.txt`
2. Run `pytest tests/`
3. Check `notebooks/demo.ipynb`

## Screenshots / Logs (if UI or training logs)

### 8. Issue Labels

| Label | Meaning |
|-------|---------|
| `good first issue` | Beginner-friendly tasks |
| `help wanted` | Open for external contributions |
| `experiment` | Unstable / exploratory work |

---

### 9. Getting Help

- **Discord:** `#contributing` channel → [https://discord.gg/u5y2Ms7m](https://discord.gg/u5y2Ms7m)  
- **Weekly office hours:** Fridays 15:00–16:00 CST *(check Discord events)*  
- **Email:** [A01665895@tec.mx](mailto:A01665895@tec.mx) *(for sensitive matters)*

---

### 10. Recognition

Top contributors are celebrated every semester via:

- 🎉 Discord shout-outs  
- 🏆 README “Hall of Fame” section  
- 🚀 Priority access to GPU hours & cloud credits  

---

Happy building!  
— **DSc AI Research Core Team**

