# Auth

This library was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.0.6.

## Setup

This library was created with:

`ng generate library auth`

It's not recommented to publish Ivy libraries to NPM repositories. It's possible and helpful to `link` the contents of `/dist`:

1. `npm build`
2. run `npm link` in the library's `dist` folder
3. run `npm link auth`

## Build

Run `ng build auth` to build the project. The build artifacts will be stored in the `dist/` directory.

## Publishing

After building your library with `ng build auth`, go to the dist folder `cd dist/auth` and run `npm publish`.

## Running unit tests

Run `ng test auth` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
