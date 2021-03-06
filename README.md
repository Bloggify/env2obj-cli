<!-- Please do not edit this file. Edit the `blah` field in the `package.json` instead. If in doubt, open an issue. -->


















# `$ obj2env`

 [![Version](https://img.shields.io/npm/v/obj2env-cli.svg)](https://www.npmjs.com/package/obj2env-cli) [![Downloads](https://img.shields.io/npm/dt/obj2env-cli.svg)](https://www.npmjs.com/package/obj2env-cli)







> Create .env files in your terminal.











[![obj2env-cli](http://i.imgur.com/yfKqx6W.gif)](#)







## :cloud: Installation

You can install the package globally and use it as command line tool:


```sh
# Using npm
npm install --global obj2env-cli

# Using yarn
yarn global add obj2env-cli
```


Then, run `obj2env --help` and see what the CLI tool can do.


```
$ obj2env --help
Usage: obj2env [options]

Create .env files in your terminal.

Options:
  -c, --comment      Add a help text for that variable.
  -d, --dir          Specify the directory where to write the .env file.
  -i, --interactive  Enables the interactive mode.
  -f, --force        Overrides the existing file without user
                     confirmation.
  -o, --output       Output the content in the stdout.
  -h, --help         Displays this help.
  -v, --version      Displays version information.

Examples:
  $ obj2env PORT NODE_ENV
  $ obj2env -o -c 'The port the app will use.' -c 'The node environment' PORT=8080 NODE_ENV

Documentation can be found at https://github.com/Bloggify/obj2env-cli#readme.
```






















## :question: Get Help

There are few ways to get help:



 1. Please [post questions on Stack Overflow](https://stackoverflow.com/questions/ask). You can open issues with questions, as long you add a link to your Stack Overflow question.
 2. For bug reports and feature requests, open issues. :bug:
















## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].
























## :scroll: License

[MIT][license] © [Bloggify][website]






[license]: /LICENSE
[website]: https://bloggify.org
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
