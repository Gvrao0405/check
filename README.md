## The Goal
To creates, manages, builds and test a web application as a part of task.

## Project Setup
# Prerequisites
You need to have Node and NPM installed on your PC.

Downloading and installing Node.js and npm

# How To Install
Download the source code using git or else download and unzip the zip file.

Open a terminal window and go to the project root folder.

You need to have npm installed globally.

Run npm i to install the required libraries.

# How To Run
Run ng serve for a dev server.

Navigate to http://localhost:4200/.

The browser will automatically reload if you change any of the source files.

# How To Run Unit Tests
To run the unit tests, you need to stop the server.

If the server is running, stop the server from the terminal window by pressing Control-C.

To run the unit tests, Run the following command in the terminal window.

ng test -- --no-watch --no-progress --browsers=ChromeHeadlessCI

And if you're running on Windows, include the --disable-gpu flag. See crbug.com/737678.

# How To Run End To End Tests
To run the unit tests using Angular cli, you need to stop the server.

If the server is running, stop the server from the terminal window by pressing Control-C.

To run the e2e tests using Angular cli, Run the following command in the terminal window.

ng e2e -- --protractor-config=e2e/protractor-ci.conf.js

And if you're running on Windows, include the --disable-gpu flag. See crbug.com/737678.

# Software Libraries Used
The following major software libraries are used:

Angular 9.0.7
CSS
rxjs        6.5.5
typescript  3.6.5
webpack     4.41.2

# UI And Program Flow
This project demonstrates how to use Angular HttpClient to do Ajax Fetch calls with API endpoints by subscribing to Observables.

It uses the  API to search for results.
Initally web pages renders images and data through api and display on the screen.On the left side we have filters by which we can filter based on the inputs given.



# Task

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.0.7.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
