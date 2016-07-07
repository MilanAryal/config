npm commands
====

npm is the package manager for JavaScript.

### Resources

* [Getting started with npm](https://docs.npmjs.com/getting-started/)

Requirements
----

Install [Node.js](https://nodejs.org/en/download/package-manager/) on your machine.

Managing global package
----

`npm ls -g --depth=0` - list out global installed packages

`npm uninstall -g [<name> [<name ...]]` - uninstall global package(s)

Managing project packages
----

`npm list` or `npm ls` (preferred shorthand) - list out currently installed npm packages

`npm ls --depth=0` - only draws out the top of the dependency tree

`npm install` -  will install both "dependencies" and "devDependencies"

`npm install --production` -  will only install "dependencies"

`npm install --dev` - will only install "devDependencies"

`npm prune [<name> [<name ...]]` - removes "extraneous" packages
