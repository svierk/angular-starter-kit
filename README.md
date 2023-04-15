# 🚀 Angular Starter Kit

![GitHub CI](https://github.com/svierk/angular-starter-kit/actions/workflows/ci.yaml/badge.svg)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=svierk_angular-starter-kit&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=svierk_angular-starter-kit)
[![codecov](https://codecov.io/gh/svierk/angular-starter-kit/branch/main/graph/badge.svg?token=W0VGTTH1VJ)](https://codecov.io/gh/svierk/angular-starter-kit)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fsvierk%2Fangular-starter-kit.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fsvierk%2Fangular-starter-kit?ref=badge_shield)

![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?logo=typescript&logoColor=white)
![RxJS](https://img.shields.io/badge/rxjs-%23B7178C.svg?logo=reactivex&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?logo=visual-studio-code&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B3263?logo=eslint&logoColor=white)
![Jasmine](https://img.shields.io/badge/jasmine-%238A4182.svg?logo=jasmine&logoColor=white)

## About the project

The repository provides a template for Angular projects which includes an initial configuration of Prettier, Linter rules, git hooks and unit tests as well as VS Code settings.

This project was generated with the [Angular CLI](https://github.com/angular/angular-cli).

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
