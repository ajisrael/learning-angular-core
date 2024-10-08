# Learning Angular

## Getting Started

### Install

First install latest version of NODE.js

Then install angular CLI:

```bash
npm install -g @angular/cli
```

See commands:

```bash
ng
```

### Create a new boiler plate project

```bash
ng new angular-course
```

Follow the prompts with no for any additional features and select CSS for styling.

Once the project has been generated `cd` into the folder and start it

```bash
cd angular-course
npm start
```

The terminal will output the url for the app you just started.

Ex: `http://localhost:4200/`

## Docs

* [Explore the Docs](https://angular.dev)
* [Learn with Tutorials](https://angular.dev/tutorials)
* [CLI Docs](https://angular.dev/tools/cli)
* [Angular Language Service](https://angular.dev/tools/language-service)
* [Angular DevTools](https://angular.dev/tools/devtools)

## Key Features

### Separation of Concerns

`.html` files hold your template or layout for a component/page

`.ts` holds the functionality

`.css` holds the design

All are very clearly separated to allow for clear separation of concerns

### Angular Template Syntax

In an `html` file on an input field you can change the `value` property to `[value]` to tell angular that the following is an expression
