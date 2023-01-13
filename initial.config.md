# Initial config

## Aplicaciones

Software que hay que traer el primer día de clase para arrancar:

- Google Chrome
- Git
- Node (versión Current)
- Visual Studio Code

## Extensiones para el VSCode

- EditorConfig for VS Code
- ESLint (de Microsoft)
- Prettier (de Prettier)
- Auto Rename Tag

- Rainbow Tags (de voldermortensen)
- vscode-icons (de VSCode Icons Team)
  
- Git Graph
- GitLens

- Sass (de Syler)
- YAML (de Red Hat)

### Opcionalmente

- Spanish Language Pack
- Code Spell Checker
- gitignore
- CodeMetrics
- Reload

- HTML CSS Support
- JavaScrip (ES6) code snippets
- ES7 + React/Redux/React-Native snippets
- CSS Modules
- vscode-styled-components (de Styled Components)
- JSON to TS

- LiveServer
- Live Share

### Si queréis mis iconos y temas, son  

- Material Icon Theme (de VSCode Icons Team)
- Dracula Official
- Peacock

## Settings para el VSCode

```json
{
  // Editor
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "editor.guides.bracketPairs": true,
  "editor.bracketPairColorization.enabled": true,
  "rainbowTags.hightlightType": "color",
  "editor.tabSize": 2,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "typescript": "typescriptreact"
  },
  "emmet.triggerExpansionOnTab": true,

  // Language
  "javascript.suggestionActions.enabled": false,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "js/ts.implicitProjectConfig.experimentalDecorators": true,
  "typescript.suggestionActions.enabled": false,
  "typescript.updateImportsOnFileMove.enabled": "always"
}
```

Estos settings los tenéis que añadir a los que ya tengáis, si no sabéis cómo, lo miramos en clase

## Git

- Si no habéis instalado Git diciéndole que VSCode sea su editor por defecto,
  para configurarlo hay que lanzar este comando:

```shell
git config --global user.name `<el vuestro>`
git config --global user.email `<el vuestro>`
git config --global core.editor "code --wait"
git config --global core.autocrlf false
git config --global init.defaultbranch main
```

13 de enero de 2023

Contenido de .editorconfig:

```editorconfig
# EditorConfig is awesome: https://EditorConfig.org
# ISDI Coders 'official'

# top-most EditorConfig file

root = true

[*]
indent_style = space
indent_size = 2
end_of_line = lf
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true
```
