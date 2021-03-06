# Chapter 3 Notes

## TypeScript

- Called it a Language, but its a superset. Not that mission critical, but worth noting.

- JavaScript - ES - ECMAScript standard for JavaScript

- ES2015 - Introduced things like Classes and Arrow Functions

- JavaScript must be transpiled if using newer features.

- TypeScript - Open source language (Started my Microsoft), Superset of JS (There we go), and Transpiles to JavaScript.

- TS is Strongly Typed - Includes things like Inline Documentation, Syntax Checking, Code Navigation, and Advanced Refactorings.

- Class Based Object Orientation

- [TypeScript Playground](https://www.typescriptlang.org/play) - Live coding in TS, see the transpiled JavaScript.

- This course focuses on "Learning TS as we go" (perf).

## Visual Studio Code

- Talks about what VSC is, and the basics of history on it.

## NPM

- She said it stands for 'Node Package Manager' (giggle)

- Command Line Utility

- Online Registry of Packages

- `npm install abc` <- standard format

- Package manager for JavaScript applications

- Installs Libraries, Packages, and Applications

- Can execute scripts (No examples here)

- Installed via Node. They installed via website (NOOOO! Recommend: `nvm`)

- `npm -v` - Checks version

## Package.json

- Need Angular, framework and libraries

- Angular CLI, command line intergace for Angular

- TypeScript - Programming Language

- Define Package.json

- `dependencies` - Packages required for development and deployment

- `devDependancies` - Packages only required for development

- Did not really go into knowing when do to what

## Setting up the Angular Application

- Starter files: https://github.com/DeborahK/Angular-GettingStarted

- Talks about installing all of the packages using `npm i`, since the dependencies already exist in the provided `package.json`.

- Talks about not running `npm audit fix`? Did not really provide a resolution. Maybe later in the course?

## Running the Angular Application

- Talks about `npm` scripts.

- Touches on `npm serve`. `-o` is the option in the CLI to open the served application in the browser.

## Modules

- ES2015 adds modules

- Angular leverages ES2015 modules

- Angular also has `Angular Modules`, which is different than ES2015 modules.

- ES2015 modules - `export class Products`, this file then becomes a module, because of the exports. And can be imported into other files.

- Importing also classifies a file as a module.

- Angular Modules, Help organize the application into coheasive blocks of logical groupings.

- `Feature Angular Modules` can contain several components. Promote application boundaries.
