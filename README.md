## Description

First microservice project with nestjs. This project is a ordering app for a restaurant. It has a menu, a list of orders and a list of users. The user can create an order, see the menu and see the orders. The admin can see the list of users, the list of orders and the menu. The admin can also create a new menu item.

based on yt video: https://www.youtube.com/watch?v=yuVVKB0EaOQ

## Run on containers
For run all services and the database on containers, you need to have docker and docker-compose installed on your machine. After use the command:
```bash
$ docker-compose up
```
If you want to rebuild the images, for example to load new dependecies, use the command:
```bash
$ docker-compose up --build -V
```
## Installation

```bash
$ pnpm install
```

## Running the app

```bash
# development
$ pnpm run start

# watch mode
$ pnpm run start:dev

# production mode
$ pnpm run start:prod
```

## Test

```bash
# unit tests
$ pnpm run test

# e2e tests
$ pnpm run test:e2e

# test coverage
$ pnpm run test:cov
```

## License

Nest is [MIT licensed](LICENSE).
