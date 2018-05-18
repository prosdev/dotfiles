**For VSCode**

- Install `ESLint` plugin: https://github.com/Microsoft/vscode-eslint
- Install `Prettier` plugin: https://github.com/prettier/prettier-vscode

**NPM Dependencies**
```
"devDependencies": {
    "prettier": "1.12.1",
    "eslint": "^4.19.1",
    "eslint-config-airbnb": "^16.1.0",
    "eslint-config-prettier": "^2.9.0",
    "eslint-plugin-import": "^2.12.0",
    "eslint-plugin-jsx-a11y": "^6.0.3",
    "eslint-plugin-prettier": "^2.6.0",
    "eslint-plugin-react": "^7.8.2"
  }
  ```
  
  **Prezto with ZSH**
  
  ```
 brew install zsh zsh-completions
 ```
 
 ```
 git clone --recursive https://github.com/sorin-ionescu/prezto.git "${ZDOTDIR:-$HOME}/.zprezto"
```

 ```
 ln -s "$rcfile" "${ZDOTDIR:-$HOME}/.${rcfile:t}"
 ```
 
 Make ZSH the default Shell: 
 ```
 chsh -s $(which zsh)
 ```
 
 Some useful `.preztorc` modules.
 
 ```
 zstyle ':prezto:load' pmodule \
  'archive' \
  'autosuggestions' \
  'git' \
  'node' \
  'osx' \
  'rsync' \
  'syntax-highlighting' \
  'terminal' \
  'editor' \
  'history' \
  'directory' \
  'spectrum' \
  'utility' \
  'completion' \
  'prompt' \
  ```
  
 
 
