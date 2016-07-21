# Manifestarium Website

### Quick start
**Make sure you have Node version >= 5.0 and NPM >= 3**

```bash
# clone the repo
# --depth 1 removes all but one .git commit history
git clone --depth 1 https://github.com/manifestarium/manifestarium-website.git

# change directory to our repo
cd manifestarium-website

# WINDOWS ONLY
# add required global libraries
# to take full advantage of TypeScript with autocomplete you have to install it globally and use an editor with the correct TypeScript plugins
# install the latest version of TypeScript (the typings library is no longer needed!)
npm install -g typescript@next webpack-dev-server rimraf webpack

# install the repo with npm
npm install

# WINDOWS ONLY
# install typings
typings install

# start the server
npm start

# use Hot Module Replacement
npm run server:dev:hmr

# if you're in China use cnpm
# https://github.com/cnpm/cnpm
```
go to [http://localhost:3000](http://localhost:3000) or [http://0.0.0.0:3000](http://0.0.0.0:3000) in your browser

# Starter seed project
[@AngularClass/angular2-webpack-starter material2 branch](https://github.com/AngularClass/angular2-webpack-starter/tree/material2)
[Documentation](https://github.com/AngularClass/angular2-webpack-starter/blob/material2/README.md)
See the documentation for how-to's, troubleshooting, understanding the project structure, etc.





