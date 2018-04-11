# AngularFireCMS
AngularCMS - HTML5, CSS3, JS and Angular5.


# Project Overview
_________________________________________________________________

AngularCMS is a simple real world webapp proyect developt in Angular5.



Now is a beta(V 1.0), as a testing project. In this proyect you can manage in the admin area:

Firebase RealTime Database, inserting data as JSON and using libraries RxJs Observables.
Admin Area deny access to unregistered users (In future implementations I'll add roles, and route permissions).
Login Area using Email and Password, Twitter, Google and Facebook.
Only Products, Users and Articles can create, delete and update from the Admin Dashboard.
Articles for Blog like Create, Read, Update and Delete Post.
E-Commerce for Shop like Create, Read, Update and Delete Products.
Article(from Blog) and Products(from Shop) has details.


# Requirements and Dependencies
________________________________________________________________

- Nodejs V. 8.9.4

- Package.json

  "dependencies": {
    "@angular/animations": "^5.2.0",
    "@angular/common": "^5.2.0",
    "@angular/compiler": "^5.2.0",
    "@angular/core": "^5.2.0",
    "@angular/forms": "^5.2.0",
    "@angular/http": "^5.2.0",
    "@angular/platform-browser": "^5.2.0",
    "@angular/platform-browser-dynamic": "^5.2.0",
    "@angular/router": "^5.2.0",
    "angular2-flash-messages": "^2.0.5",
    "angularfire2": "^5.0.0-rc.5-next",
    "core-js": "^2.5.5",
    "firebase": "^4.12.1",
    "ngx-cookie-service": "^1.0.10",
    "rxjs": "^5.5.9",
    "zone.js": "^0.8.26"
  },
  "devDependencies": {
    "@angular/cli": "^1.7.4",
    "@angular/compiler-cli": "^5.2.0",
    "@angular/language-service": "^5.2.0",
    "@types/jasmine": "~2.8.3",
    "@types/jasminewd2": "~2.0.2",
    "@types/node": "^6.0.105",
    "codelyzer": "^4.0.1",
    "jasmine-core": "~2.8.0",
    "jasmine-spec-reporter": "~4.2.1",
    "karma": "~2.0.0",
    "karma-chrome-launcher": "~2.2.0",
    "karma-coverage-istanbul-reporter": "^1.2.1",
    "karma-jasmine": "~1.1.0",
    "karma-jasmine-html-reporter": "^0.2.2",
    "protractor": "~5.1.2",
    "ts-node": "~4.1.0",
    "tslint": "~5.9.1",
    "typescript": "~2.5.3"
  }

# Proyect Installation
________________________________________________________________

First, download the proyect from Git: https://github.com/Borjacs1991/AngularFireCMS

Execute in NodeJS:
> npm install 

Add your Firebase proyect Web App code in environment.ts:

export const environment = {
  production: false,
  firebase: {
    apiKey: "",
    authDomain: "",
    databaseURL: "",
    projectId: "",
    storageBucket: "",
    messagingSenderId: ""
  }
};

It should be fine to start working with this proyect, now lets start it fron Node Command Line:

>ng serve -o

# Future Revisions/Updates
_____________________________________________________________

 - Roles:
    * Admin has full control in the App.
    * Admin can create User with roles.
    * Editor can create and edit Articles and Products.
    * Subscriber can't access to Admin dashboard, but is able to read the blog content and check products.

 - Slider component:
    * Admin has full control in the Slider component.
    * Editor can edit the Slider content.
    
 - E-Commerce:
    * Subscriber can add a product in the basket, and the product will be hold as cookie or localStorage.
    * Subscriber need to be logged for purchase a product.
 
 - Other realted Implementations:
    * Images.
    * Cookie policy declaration(pop-up).
    
    
# More info 
______________________________________________________________

https://angular.io/guide/quickstart



