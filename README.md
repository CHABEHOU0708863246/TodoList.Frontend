# TodoListFrontend

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.2.5.

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



## Création des composants angular

Créez l'application Composants angular. L'application aura quatre composants et un composant enfant. Le composant todo-items, le composant enfant todo-item-form, le composant home, le composant login et le composant registrer

ng g c todo-items -s
ng g c todo-items/todo-item-form -s
ng g c home -s
ng g c login -s
ng g c register -s


## Création des modèles

Création d'un dossier appelé models qui contiendra un modèle de connexion, un modèle d'enregistrement et un modèle d'élément de tâche

ng g class models/todo-item --type=model
ng g class models/login --type=model 
ng g class models/register --type=model 



## Création des services

dans le dossier services

ng g s services/auth-guard
ng g s services/todo-app



## Mise à jours des fichiers de modèles

export class TodoItem {
    Id: number=0;
    Name: string="";
    Description: string="";
    Status: string="";
}

export class Login {
    Username: string="";
    Password: string="";
}

export class Register {
    Username: string="";
    Email: string="";
    Password: string="";
}



## Mise à jour des fichiers de service

**todo-app.service.ts**



**auth-guard.service.ts **

Installation de la bibliothèque angular2-jwt en exécutant la commande suivante :

```bash
npm install @auth0/angular-jwt
```



## Mettre à jour le fichier app.module.ts

Installez la bibliothèque ngx-toastr en exécutant la commande suivante :

```bash
npm i ngx-toastr
```



## Mettre à jour les fichiers de composants

**app.component.html **

```markup
<div class="container">
  <router-outlet></router-outlet>
</div>
```

**home.composant.ts**

**home.composant.html**

**login.component.ts**

**login.composant.html**

**register.component.ts**

**register.component.html**

**todo-item-form.component.ts**

**todo-item-form.component.html**

**todo-items.component.ts**

**todo-items.component.html**
#   T o d o L i s t . F r o n t e n d  
 #   T o d o L i s t . F r o n t e n d  
 #   T o d o L i s t . F r o n t e n d  
 