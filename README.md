# TypeScript Seed
Setting up new TypeScript projects can be quite the chose, so I decided to create a neat starter project. This package should contain all the stuff you need to get started with TypeScript.

Make sure to edit all of the fields in ```package.json``` before you use the project 😉.

## NPM Scripts
This project contains a number of scripts to make working with a TypeScript project easier. Each of these scripts may be run with ```npm run [script-name]```

### build
Transpiles all the TypeScript sources into JavaScript that is usable by node.

### watch
The watch command transpiles your TypeScript sources into JavaScript, usable by node. Every change in the TypeScript source will cause the script to re-transpile all of the sources and execute them. Debugging will be turned on.

### debug
Transpiles TypeScript sources and runs them, with debugging turned on.

### do-publish
This command transpiles all of your soures and publishes the finished work to the NPM registry. You need to be logged in for this command to work.
