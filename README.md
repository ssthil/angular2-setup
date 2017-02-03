# Setting up an Angular 2 Development Environment

In this tutorial, we’ll avoid using the CLI and learn how to set up our development environment from scratch.

Thanks to the "target": "es5" option, TypeScript will transpile our ES6 code to ES5 so that all browsers can understand the JavaScript code we write.

## Set up Your Base Project

Quickly go ahead and create a new directory, `newapp`. Move into the directory and create an `index.html`

### package.json

Create another file, `package.json` by running the `npm init` command from the terminal. You can simply just type enter several times throughout all the questions been asked to speedily create the file.

### lite-server

Let’s install a package, `lite-server`, that will allow us to serve our application like so:

```
npm install --save-dev lite-server
```

Open up package.json to configure lite-server like so:

