# To start the frontend service
$ ng s

# To start the frontend service in the background
$ sudo npm install -g pm2
$ pm2 start "ng serve"

When deploy it to production, remember to update the host info in src/environments/...; Please also note, when using ssh to login to a remote linux to deploy the service. Always use Ctrl+D to close the ssh connection, otherwise the background job might be shutdown incorrectly.

# Test users:
username: gkvoid1@gmail.com
password: 1234567890

# MyStoreFrontEnd

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.2.10.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
