### Paste this into a terminal as one command to install all the extensions I use for Vue 3 + Vite.
```
code --install-extension adammaras.overtype
code --install-extension antfu.browse-lite
code --install-extension antfu.vite
code --install-extension bradlc.vscode-tailwindcss
code --install-extension christian-kohler.npm-intellisense 
code --install-extension christian-kohler.path-intellisense
code --install-extension csstools.postcss
code --install-extension DavidAnson.vscode-markdownlint
code --install-extension dbaeumer.vscode-eslint
code --install-extension eamodio.gitlens
code --install-extension esbenp.prettier-vscode
code --install-extension formulahendry.auto-close-tag
code --install-extension mhutchie.git-graph
code --install-extension mikestead.dotenv
code --install-extension ms-python.python
code --install-extension ms-python.vscode-pylance
code --install-extension ms-toolsai.jupyter sai.jupyter-keymap
code --install-extension ms-toolsai.jupyter-renderers
code --install-extension ms-vscode.vscode-typescript-tslint-plugin
code --install-extension nick-rudenko.back-n-forth
code --install-extension sdras.vue-vscode-snippets
code --install-extension sibiraj-s.vscode-scss-formatter
code --install-extension steoates.autoimport
code --install-extension streetsidesoftware.code-spell-checker
code --install-extension syler.sass-indented
code --install-extension Tyriar.sort-lines
code --install-extension VisualStudioExptTeam.vscodeintellicode
code --install-extension Vue.volar
code --install-extension Wscats.vue
code --install-extension xabikos.JavaScriptSnippets
code --install-extension zjffun.gotofolder
```

### To create a list of your installed extensions, run:
```
code --list-extensions | % { "code --install-extension $_" }
```
The output can be saved or pasted into another terminal to share the love.

Credit to <a href="https://stackoverflow.com/questions/35773299/how-can-you-export-the-visual-studio-code-extension-list" target="_blank">this guy on StackOverflow</a>