# So you want to be a Vue developer...
###### 1. Essential Global Packages

- [NodeJs](https://nodejs.org/en/download/)
  -- NodeJs's installation includes Chocolatey, a windows package manager, so commands that begin with `chocho` should be executable from any admin console.
- [Yarn](https://yarnpkg.com/) package manager is a faster alternative to Npm. Yarn is maintained by Facebook.  It will replace your `npm` console commands. 
    - To install run:`choco install yarn`
    Check out package.

###### 2. Browser Tools
- Vue Dev Tools _(Browser Extension available in Chrome Store/ Firefox)_

###### 3. Vs Code Extensions
- You can install appropriate extensions all at once by pasting in the contents of `ExtensionsScripts.md` into your terminal.  

    To create a list of your installed extensions, run:
    ```
    code --list-extensions | % { "code --install-extension $_" }
    ```
    The output can be saved or pasted into another terminal to share the love.  _All credit to <a href="https://stackoverflow.com/questions/35773299/how-can-you-export-the-visual-studio-code-extension-list" target="_blank">this guy on StackOverflow</a>_

###### 4. Vs Code Settings
- Typical Keybindings, Settings, Snippets location:

    - `C:\Users\[User Name]\AppData\Roaming\Code\User`
  
