# angular2-quickstart
Setup Angular Project with required Files and directories

Steps to setup custom dist or output directory
1. Change dist directory mapping in systemjs.config.js
    app: 'app'    --->    app: 'dist'

2. Add outDir in the tsconfig.json

    "outDir" : "dist"

3. run npm start
