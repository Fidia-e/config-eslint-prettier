# Getting Started

Installer lesd 3 extensions:

- Prettier - Code formatter
- Pretter - ESLint
- ESLint

Installer prettier et les plugins eslint pour prettier
`yarn add prettier eslint-config-prettier eslint-plugin-prettier prettier-eslint --dev`
`npm i prettier eslint-config-prettier eslint-plugin-prettier prettier-eslint --save-dev`

Initialiser Eslint en cli `npx eslint --init`
Questions:

- How would you like to use ESLint? : To check syntax, find problems, and enforce code style
- What type of modules does your project use? : JavaScript modules (import/export)
- Which framework does your project use? : React
- Does your project use TypeScript? No / Yes
- Where does your code run? : Browser
- Use a popular style guide, : (ne rien mettre)
- What format do you want your config file to be in? JavaScript

Créer un fichier .prettierrc à la racine du projet, y mettre ce qu'il y a dans ce repo

Ajouter le contenur du fichier .eslintrc
Vérifier que `'prettier'` est bien ajouté dans À LA FIN des tableaux 'extends' et 'plugins'

Ajouter ces lignes dans le fichier settings.json de VSC:

```json
  "editor.formatOnSave": true,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
      "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
  },
```
