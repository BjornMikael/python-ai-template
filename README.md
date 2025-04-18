# 🧠 Python AI Project Template
![Langchain](https://img.shields.io/badge/Langchain-%F0%9F%A7%A0-blueviolet)
![OpenAI](https://img.shields.io/badge/OpenAI-API-green)
![Poetry](https://img.shields.io/badge/Poetry-Dependency--Manager-blue)
![Copier](https://img.shields.io/badge/Copier-Template-yellow)
![VSCode Ready](https://img.shields.io/badge/VSCode-Settings%20Included-purple)

A ready-to-use project template for building modern AI-powered Python apps using [Langchain](https://github.com/langchain-ai/langchain), [OpenAI](https://platform.openai.com/), and a polished dev workflow.

---

## 🚀 Features
✅ **Langchain + OpenAI starter code**  
✅ **Poetry** for dependency management  
✅ **VS Code settings** for Black, Ruff, Pyright  
✅ **.env integration** for secrets  
✅ 🧪 Built-in testing with `pytest`  
✅ 🧰 Reusable with [Copier](https://copier.readthedocs.io/)  
✅ 🧹 Clean project structure and `.gitignore`

---

## 📁 Folder Structure
```
my-project
├── .vscode
│   └── settings.json
├── .env.example
├── main.py
├── pyproject.toml
├── README.md
├── scripts
└── copier.yml
```

---

## 🧙‍♂️ Usage
```bash
copier copy gh:BjornMikael/python-ai-template your-new-project
cd your-new-project
poetry install
cp .env.example .env  # Add your API key
poetry run python main.py
```

## 🔐 .env Format
```env
OPENAI_API_KEY=sk-...
```

## ⚙️ How It Works
This template is powered by Copier, a modern project templating engine.

1. **Scaffold with Copier**
   ```bash
   copier copy gh:BjornMikael/python-ai-template your-project
   ```
   🪄 Prompts you for your project name and sets up all files automatically.

2. **Install dependencies with Poetry**
   ```bash
   poetry install
   ```
   📦 Handles all Python and dev tool dependencies in one command.

3. **Load your API key**
   ```bash
   cp .env.example .env
   # Then paste your OpenAI key inside
   ```

4. **Start coding**
   Edit main.py, use Langchain & OpenAI, and extend as needed. Supports CLI apps, agents, streamlit/gradio UIs, and more.

## 👨‍🎓 Who's It For?
- Building OpenAI/LLM tools
- AI bot experiments & CLI tools
- Portfolio projects & tutorials
- Devs who want a clean Python + VS Code + Poetry base

## 🌟 Give it a ⭐ if you like it!
Built with ❤️ by BjornMikael
