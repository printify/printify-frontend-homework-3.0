# CodingTask: Vending Machine

Inside the angular app in the src directory find a generated component `VendingMachine`. Use your initiative to build a functioning visual respresentation of a vending machine.

[Angular Material](https://material.angular.io/components/categories) is installed if you wish to use it.

### Products in the Vending Machine:

* A - costs USD 0.95
* B - costs USD 1.26
* C - costs USD 2.33

### Business rules:

1. The machine accepts coins of 1, 2, 5, 10, 20, and 50 cents.

2. It allows the user to choose from 3 different products by entering coins (Ex: `20 20 10 1 5`) and selecting a product (Ex: `A`, `B`, `C`)

3. Then the machine gives out the change in the least possible amount of coins. (Ex: `50 50 20 5 2 1`)

<!-- 1. Create a component with a list of 3 clickable items:
    - product A (price: 0.95 USD)
    - product B (price: 1.26 USD)
    - product C (price: 0.95 USD)
2. Add a form input "Input amount (USD)"
3. Display last-bought product, and change given
    - in coin denominations (1, 2, 5, 10, 20, 50 cents and 1 dollar)
    - with the least number of coins possible
4. Display an error and prevent purchases if the input amount is too low -->


-------------------

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.1.0.

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
