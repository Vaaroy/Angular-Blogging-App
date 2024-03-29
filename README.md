# Angular8 - Angular Blogging App + MDBootstrap + Firebase 



Developing a **Blogging App (Education) Application using Angular8**.


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.1.1.


## Functionalities

1.  User Registration using Firebase Authentication (using Email/Password | Google Authentication )
2.  CRUD Operations like

- User can add blog to his List.
- Admin can add Blog to the Blog list
- Admin can edit/delete the Blog.



1.  Security

- Implmented Authentication and Authorization

## Tools and Technologies

- Technology: HTML, MDBootstrap, CSS, Angular-7, Firebase, i18n, Drag & Drop, Progressive Web Application, jsPDF (to download Receipt as PDF).
- Database : Angular Firebase.

#### This Projects covers all fundamentals of Angular

- Multiple Modules
- Components, Template and DataBinding
- Form Validation
- HttpClient
- Animations
- Dependency Injection
- Routing & Navigation
- Service Workers
- Pipes
- Gaurds etc..

# Installation

1.  Angular CLI
    - [Download Angular CLI](https://cli.angular.io/)
2.  NodeJs
    - [Download Nodejs](https://nodejs.org/en/download/)
3.  Package Manager - NPM / Yarn
4.  Clone the repository and run `npm install` if you use **npm** as package manager or `yarn install` if you use **yarn** as package manager.
5.  Angular + Firebase Tutorial - [Angular + Firebase + Typescript — Step by step tutorial](https://medium.com/factory-mind/angular-firebase-typescript-step-by-step-tutorial-2ef887fc7d71)
6.  Activate Firebase Authentication Providers

    `Authentication -> Sign-in-method -> Enable Email/Password & Google provider`

7.  Update the Firebase Database Rules

    `Database -> Rules`

    ```
    {
    "rules": {
        ".read":true,
        ".write": true
    }
    }
    ```

8.  Configure your firebase configuration `src/environments/firebaseConfig.ts`

    ```
    export const FireBaseConfig = {
        apiKey: "YOUR_API_KEY",
        authDomain: "YOUR_AUTH_DOMAIN",
        databaseURL: "YOUR_DATABASE_URL",
        projectId: "YOUR_PROJECT_ID",
        storageBucket: "YOUR_STORAGE_BUCKET",
        messagingSenderId: "YOUR_SENDER_ID"
    };
    ```

9.  For Admin Role `Register or SignIn with Google Auth`

    your registered data will be saved inside the firebase **clients** table.

    ```
        -clients
            -LRSkWxGAKQAFZmyfsx6
                -createdOn: "1542046725"
                -email: "<<YOUR_REGISTERED_EMAIL_ID>>"
                -isAdmin: false      <--- Change this to true
                ...
    ```

    Now you can able to access the Admin Privileges like `Creating Product, Removing Product, etc..`

10. Run the Server.

## Screenshots:

### Home Page:

![Alt text](https://github.com/Vaaroy/Angular-Blogging-App/blob/master/screenshots/Screenshot1.PNG "Home Page")

### Blog List Page:

![Alt text](https://github.com/Vaaroy/Angular-Blogging-App/blob/master/screenshots/Screenshot2.PNG "blog Page")



## How can I support the developer ?

* Star my Github repo ⭐
* Create pull requests, submit bugs, suggest new features or documentation updates 🛠

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


## Somethings wrong!!

- If you find that something's wrong with this package, you can let me know by raising an issue on the GitHub issue tracker


