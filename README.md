# MICROBOOT

Microservices using SpringBoot Backend and Angular Frontend.

## TODO App

The Todo App is an Angular Frontend to the SpringBoot Todo Backend <https://github.com/adanlessossi/todo-rest-backend>

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.8.

What we are trying to do here is to:

- Connect the Angular Frontend with SpringBoot Rest Backend
- Used Guarded Routes to secure the application
- Tested out Basic Authentication
- Tested out Authentication using JWT
- Used Angular HttpClient to create CRUD to the Backend
- Used Angular HttpInterceptor to inject Authorization Headers to Requests.

## TODO Rest Backend

This application aims to illustrate the use of SpringBoot REST Backend API to serve a 'Todo' Angular Frontend.

In this application, we are trying to use:

- Spring Boot Data-Jpa
- Spring Boot Security
- Authentication using JWT

## Getting Started

Clone the repositories to your local computer.

### Prerequisites

To make this code run, you will certainly need install:

- Java 8 or above
- Maven 3.5.x
- An IDE of your choice
- Angular version 7.+
- node version 10.+
- npm version 6.+

### Generate a new Password

To create et new Password for the sample Application, you will need to generate it from the class `BCryptEncoder`, and then change the token and username in the class `JwtInMemoryUserDetailsService`.

## Running the Backend

Open the Main class `RestBackendApplication` and Run-As 'Java Application', (depending on your IDE).

### Running the Frontend

Run `npm install` to install the dependencies.
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Built With

- [Spring-Boot](https://spring.io) - The Spring Boot framework
- [Maven](https://maven.apache.org/) - Dependency Management
- [Angular](https://angular.io/) - The Angular Framework
- [NodeJS](https://nodejs.org/en/) - The Node Framework

## Authors

- **Bernard Adanlessossi** - _Initial work_

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

- **Thomas Wenger**
- **Business & Decision**
