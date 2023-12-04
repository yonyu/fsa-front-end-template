# FsaFrontEndTemplate

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.0.5.

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

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Add a few files
### Allow the frontend and backend to talk to each other on the same machine for local development
proxy.config.json

ng serve

open the source file at src/app/app.component.html
delete everything except the line below:
<router-outlet></router-outlet>

# create components at the folder /fsa-front-end-template
ng generate component back-button
ng g c small-x

# update the components 'back-button' and 'small-x'

# Copy and paste some css into styles.css under the project root
https://github.com/shaunwa/full-stack-angular-projects/
https://github.com/shaunwa/full-stack-angular-projects/fsa-members-only/src/styles.css
https://github.com/shaunwa/full-stack-angular-projects/blob/b72b4e526bcb9d6e1b2f9d39e147ba2788c293af/fsa-members-only/src/styles.css

# commit changes to your github accounts:
github.com/
new tempate to Create a new repository
git add .
git commit -m "Completed template"
## copying the commands from https://github.com/yonyu/fsa-front-end-template
git remote add origin https://github.com/yonyu/fsa-front-end-template.git
git branch -M main
git push -u origin main



