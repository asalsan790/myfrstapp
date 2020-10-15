# Myfirstapp

# según
https://www.youtube.com/watch?v=AR1tLGQ7COs&feature=emb_logo

# Instalacion de Angular pasos
Trabajamos con google chrome
Instalar visual studio code
Instalar nodejs
Instalar git
Puede ser práctico deshabilitar credential helper
Angular lo instalamos con: https://cli.angular.io/

Según aparece en la web anterior:

npm install -g @angular/cli
ng new my-dream-app  // Crea el nuevo proyecto Angular
cd my-dream-app
ng serve

*npm install -g @angular/cli*
Esto no crea un proyecto de Angular pero sí una herramienta 
que genera proyectos de Angular (ng)

*ng serve*  // Crea el servidor de desarrollo
http://localhost:4200/

Si quiero crear un componente:
ng generate component hola-mundo

PS C:\Users\Administrador\Documents\adolfo\AA_ProGit\angular001\myfirstapp> ng g component hola-mundo
CREATE src/app/hola-mundo/hola-mundo.component.html (25 bytes)
CREATE src/app/hola-mundo/hola-mundo.component.spec.ts (648 bytes)
CREATE src/app/hola-mundo/hola-mundo.component.ts (290 bytes)
CREATE src/app/hola-mundo/hola-mundo.component.css (0 bytes)
UPDATE src/app/app.module.ts (491 bytes)
PS C:\Users\Administrador\Documents\adolfo\AA_ProGit\angular001\myfirstapp>

En app.component.html escribimos solo la línea:

  <app-hola-mundo></app-hola-mundo>  



# a partir de aquí generado con la instalación
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.1.4.

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
