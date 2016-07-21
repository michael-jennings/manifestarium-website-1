# Manifestarium Website

### Pre-requisites
** Make sure you have Node version >= 5.0 and NPM >= 3**

### Quick Setup
```bash
# let setup.bat handle the setup steps
setup
```

### Manual Setup
```bash
# add required global libraries
# to take full advantage of TypeScript with autocomplete you have to install it globally and use an editor with the correct TypeScript plugins
# install the latest version of TypeScript (the typings library is no longer needed!)
npm install -g typescript@next webpack-dev-server rimraf webpack

# install project libraries
npm run clean:install
```

### Start the server
```bash
# start the server using Hot Module Replacement
start-hmr

# start server without Hot Module Replacement
start
```

### Starter Seed
[@AngularClass/angular2-webpack-starter material2 branch](https://github.com/AngularClass/angular2-webpack-starter/tree/material2)
[Documentation](https://github.com/AngularClass/angular2-webpack-starter/blob/material2/README.md)
See the documentation for how-to's, troubleshooting, understanding the project structure, etc.





