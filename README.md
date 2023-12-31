# CRUD

<div style="display:flex; flex-wrap:wrap; justify-content:center; margin:auto">
   <img style="width:1000px; height:450px; margin:12px" src="https://github.com/LolaGM/CRUD-Form/assets/116545851/94d0de4f-396f-49c7-a913-9c43a1bd9b71">
</div>


## CRUD Form
CRUD using observables RXJS with components form and table connected


## Basic installation

<ol>
    <li>Once the code is cloned, use the command <code>npm install</code> to have all necessary modules</li>
    <li>After installing the node_modules, run <code>ng s -o</code> command. For this command to work, remember to run this command in the same directory where the <code>package.json</code> is located</li>
    <li>You need to run the backend part using <code>npm run backend </code> and use <code>npm install -g json-server</code></li>
    <li>Sweet Alert 2 and Bootstrap are used for UX / UI </li>
</ol>

## Create a JSON server

<p>JSON Server is an npm package that allows you to create REST JSON web service, backed by a simple database. It is created for front end developers and helps to perform all CRUD operations without a proper backend prototype or structure. A valid json file will suffice.</p>

<ol>
    <li>Run the below command in the terminal.<code>npm install Json-server</code></li>
    <li>Create a sample json file with data: <code>db.json</code>. Make sure of the location of the file: Don’t create mock data files under /src/assets/ or /src/app/ folder.
.</li>
    <li>You can run the server in two ways: 1 -use the command line <code>json-server –watch db.json</code> or you can add this line to the package.json file in section scripts: <code>"backend": "json-server --watch db.json --port 3000",</code>and run the server with <code>npm run backend
</code></li>
<li>Your JSON Server will be running on port 3000. The below data will be shown in the terminal
</li>
</ol>

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.0.5.

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
