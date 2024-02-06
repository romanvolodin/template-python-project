# Шаблон Python проекта

## Как использовать

Перейдите в корень проекта и выполните следующие команды в консоли:

```bash
repoUrl=https://raw.githubusercontent.com/romanvolodin/template-python-project/main

curl $repoUrl/.editorconfig > .editorconfig
curl $repoUrl/Python.gitignore > .gitignore
curl $repoUrl/README_TEMPLATE.md > README.md
curl $repoUrl/pyproject.toml > pyproject.toml
curl $repoUrl/requirements-dev.txt > requirements-dev.txt
curl $repoUrl/requirements.txt > requirements.txt
curl $repoUrl/.env.template > .env
```

Скопируем настройки VS Code:

```bash
mkdir .vscode
curl $repoUrl/.vscode/settings.json > .vscode/settings.json
```
