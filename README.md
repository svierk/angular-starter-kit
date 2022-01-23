# 🚀 Angular Starter Kit

The repository provides a template for Angular projects which includes an initial configuration of Prettier, Linter rules, git hooks and unit tests as well as VS Code settings.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.1.2.

## Getting started

To get the template up and runnning locally, all you need to do is open the repository with VS Code, install all the recommended extensions and run `npm install` to install all required dependencies.

## Git hooks

The project includes client-side pre-commit git hooks using [husky](https://github.com/typicode/husky) and [lint-staged](https://github.com/okonet/lint-staged). After installing all project dependencies, Prettier and Linter are automatically executed before each commit.

## Development server

Run `npm start` or `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `npm run build` or `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Prettier

Run `npm run prettier` to check for _Prettier_ issues and `npm run prettier:fix` to automatically fix those _Prettier_ issues.

## Linter

Run `npm run lint` to check for _ESLint_ issues and `npm run lint:fix` to automatically try to fix those _ESLint_ issues.

## Running unit tests

Run `npm run test` or `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io) in watch mode. By running `npm run test:coverage` you can execute all unit tests with code coverage.

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
