I have written an article to help you understand this NestJS application code. You can find it here: [`NestJS App with Authentication: Login and Signup`](https://www.linkedin.com/pulse/nestjs-app-authentication-login-signup-moaz-irfan)

The Frontend dashboard repo to serve this backend service is here: [`Frontend-Dashbard`](https://github.com/MoazIrfan/Frontend-NestJS-Authentication-Login-Signup)


## Setting up Project 
Open PostgreSQL command line interface and run: 
```
CREATE DATABASE nestjs;
```
("Replace 'nestjs' with your preferred database name, and make sure to use that same name in your .env file."). Tables will be auto generated.

## Description 

NestJS authentication application that includes login and sign-up functionalities. Used a PostgreSQL database and connected it to NestJS. To manage a database easier, used an Object-relational mapping (ORM) tool called TypeORM.

## Installation

```bash
$ yarn install
```

## Running the app

```bash
# development
$ yarn start

# watch mode
$ yarn start:dev

# production mode
$ yarn start:prod
```

## Test

```bash
# unit tests
$ yarn test

# e2e tests
$ yarn test:e2e

# test coverage
$ yarn test:cov
```

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## License

Nest is [MIT licensed](LICENSE).
