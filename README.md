# ProjectOne

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.0.2.

## Project Description

This small project is based on employees submitting reimbursements through a company website, and managers approving or denying those reimbursements

## Technologies Used
  * Angular (Web Framework)
  * Eclispe (IDE)
  * PostgreSQL (Database)
  * Javalin (Web FrameWork
  * Apache Maven (Dependecy Management)
  * Java (Programming language)
  * Microsoft Visual Studio Code (Source Code Editor)
  * Postman (API Framework)
  * Apache Log4j2 (Logging Utility)
  * JDBC (Java Database Connectivity)
  
## Features
  * Employees can submit reimbursements (tracks which employee is submitting by user ID)
  * Employees can view their pending and resolved reimbursements seperately
  * Employees can update their profile infomation (Address & Password for now)
  * Reimbursement's submitted date value is automatically updated once an managers decides on the reimbursement
  * Reimbursement's created date value is automatically updated when a employee submits a reimbursement
  * Managers can decide on employee's reimbursements through the usage of an dropdown menu listing the options
  * Managers can choose an employee in the Employee-List section, and it will list all reimbursement tied to that employee
  * Home menu display's the user's username (Only displays name, will implement more designs)
  * Reimbursements, employees, managers are all stored in the database, PostgreSQL
  
## To-do List
  * Add design templates to the website for each section
  * Add form validations for login, and update sections
  * Convert backend code to SpringBoot
  * Logout function
  * Add test cases to frontend
  * Add Unit testings
  
## Front-end Setup
  Before running the front-end side, open your Command Prompt/Power Shell then change your directory to the  frontend project folder(Project One-Frontend.
  Once you've done that type in 'npm install' to install .angular and node-modules dependencies.
## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
