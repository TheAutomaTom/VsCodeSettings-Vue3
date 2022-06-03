# Yarn
- `yarn` = `npm install` 
- `yarn.lock` replaces `package-lock.json`
    - You should delete `package-lock.json`, if present
    
- If `yarn` ever acts funny, 
    1. Delete `node_modules` folder
    2. Run `yarn cache clean && yarn upgrade && yarn`

# Vite
- To debug locally, run `yarn dev`

    _Typescript Note..._
    
    Typescript will let you get away with changes made during debugging that will throw compiler errors after you've rebooted your app.  It's a good habit to cash your test server frequently with `Ctrl + 'C'` and recompile. 
