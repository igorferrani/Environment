# Environment
Configurações de ambientes de desenvolvimento para Linux OS - Ubuntu 17.10

### Comandos NPM
#### salvar preferências locais no diretório do repositório local
```
npm run save
```

#### Carregar configurações para a máquina
```
npm run load
```

### VSCode
#### KeyBindings
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

#### User Settings
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