# Environment
Configurações de ambientes de desenvolvimento para Linux OS - Ubuntu 17.10

Pra rodar o script de instalação, execute o comando na raiz do projeto
```
./install.sh
```

## VSCode
### KeyBindings
---
File path: ~/.config/Code/User/keybindings.json
---
```
// Place your key bindings in this file to overwrite the defaults
[
    {
        "key": "ctrl+shift+up",
        "command": "editor.action.transformToUppercase",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+shift+down",
        "command": "editor.action.transformToLowercase",
        "when": "editorTextFocus"
    }
]
```

### User Settings
---
File path: ~/.config/Code/User/settings.json
---
```
{
    "team.showWelcomeMessage": false,
    "editor.lineHeight": 30,
    "workbench.colorTheme": "Monokai"
}
```