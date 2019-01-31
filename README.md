# Node Project Boilerplate

[Docker Compose](https://docs.docker.com/compose/install/) is needed to set up this project on
dev machine.

NodeJs and RabbitMQ docker images are used.

----
## Commands

To start the docker container
```sh
$ docker-compose -f docker-compose.dev.yml up
```

To build/rebuild the docker container
```sh
$ docker-compose -f docker-compose.dev.yml build
```

To run the tests
```sh
$ npm test
```
To check code for linting
```sh
$ npm run lint
```
To fix linting
```sh
$ npm run lint:fix
```
To compute coverage
```sh
$ npm run test:coverage
```