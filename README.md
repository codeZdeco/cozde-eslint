## CoZde Eslint rules for react typescipt projects

## How to use this?

### 1. Link eslint to your project

Run the following command at your root project folder:  
`npm link cozde-eslint`

### 2. Manual install all peer dependencies

For npm  
`npm i -D @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint-config-prettier eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks eslint-plugin-simple-import-sort prettier`

For yarn  
`yarn add -D @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint-config-prettier eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks eslint-plugin-simple-import-sort prettier`

### 3. Custom your `eslintConfig` in `package.json`

```json
"eslintConfig": {
    "extends": [
      "cozde-eslint"
    ]
  }
```

Or edit your `.eslintrc` file

```json
{
  "extends": ["cozde-eslint"]
}
```
