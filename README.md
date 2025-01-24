# ProductManagerWebsite

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.0. It is a simple product management application built with **Angular**, **PrimeNG**, and **RxJS (BehaviorSubject)**. The application demonstrates basic CRUD (Create, Read, Update, Delete) operations on a list of products, along with features like search, pagination, sorting, and visual feedback (toast messages) provided by PrimeNG components.

## Development server

Run `npm install` to install the required dependencies. After that, run `ng serve` for a dev server. Navigate to [http://localhost:4200/](http://localhost:4200/). The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Key Features

- **PrimeNG Components**: Uses PrimeNG table (`p-table`), dialog (`p-dialog`), toast (`p-toast`), and other UI components for a rich user experience.
- **Reactive Data Management**: Products are managed via a `BehaviorSubject` in an Angular service, allowing live updates to the UI.
- **CRUD Operations**: Users can create new products, edit existing ones, or delete single/multiple products.
- **Search and Sorting**: Built-in PrimeNG features allow for quick search and column-based sorting.
- **Angular Best Practices**: Follows Angular CLI project structure, TypeScript typing, and component-based architecture.
