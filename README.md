# Автоматическое исправление ошибок при сохранении файлов

Автоматическое исправление ошибок при сохранении файлов реализовано в файле settings.json

    {
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode",
        "editor.codeActionsOnSave": {
            "source.fixAll": true
        },
        "editor.formatOnSave": true
        }
    }

Файл находится в папке .vscode