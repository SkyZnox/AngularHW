# My explicative part for the homework

So, for this project, I had to set up two workflows using GitHub Actions. 

The first one, named Linter Angular from the linter.yaml, processes when a pull request is done from one branch to the main branch. It runs the Angular lint using 
this command `npm run lint`. 

The second one, named Deploy to GitHub Pages from the deploy.yaml, processes when a push is done on the main branch. It builds the project and deploys the build
directly on GitHub Pages.

So after each push on main, I'll be able to see my project on this link : https://skyznox.github.io/AngularHW/


If I want to deploy my project on each pull request done to the main branch, it's pretty easy to change on the deploy.yaml. 

## Author

Homework done by M.C

---

# Generated Part

# Angular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.2.7.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
