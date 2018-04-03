# OnlineRetailStore

##### A web app of a record store with a database.  4/2/18  

# Description
This is an Epicodus practice project for week 4 of the JavaScript course.  Its purpose is to display understanding of Angular and Firebase.  

## Technologies Used
* HTML
* CSS
* Bootstrap
* JavaScript
* Node JS
* Angular
* Firebase  

## Installation

clone the github respository
```
$ git clone https://github.com/Sara-Hamilton/online-retail-store
```
## Add Firebase Credentials
Create an account and get credentials from Firebase. https://firebase.google.com/   
Create a new project.  
Give it the name of your choice.  
Select your Country/Region.  
Choose the add Firebase to your web app option.  
Add a file named api-keys.ts in the src/app directory.  

Add the following code to the file with your credentials in place of xxxx.
```
export var masterFirebaseConfig = {
    apiKey: "xxxx",
    authDomain: "xxxx.firebaseapp.com",
    databaseURL: "https://xxxx.firebaseio.com",
    storageBucket: "xxxx.appspot.com",
    messagingSenderId: "xxxx"
  };
```

##  Run the Program  
move into the directory
```
$ cd quasi-etsy
```  
install npm
```
$ npm install
```
run the program
```
$ ng serve --open
```

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.5.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
