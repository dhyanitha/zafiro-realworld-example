# zafiro-realworld-example

[![Join the chat at https://gitter.im/inversify/InversifyJS](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/inversify/InversifyJS?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![npm version](https://badge.fury.io/js/zafiro.svg)](http://badge.fury.io/js/zafiro)
[![Build Status](https://travis-ci.org/remojansen/zafiro-realworld-example.svg?branch=master)](https://travis-ci.org/remojansen/zafiro-realworld-example)
[![Dependencies](https://david-dm.org/remojansen/zafiro-realworld-example.svg)](https://david-dm.org/remojansen/zafiro-realworld-example#info=dependencies)
[![img](https://david-dm.org/remojansen/zafiro-realworld-example/dev-status.svg)](https://david-dm.org/remojansen/zafiro-realworld-example/#info=devDependencies)
[![Known Vulnerabilities](https://snyk.io/test/github/remojansen/zafiro-realworld-example/badge.svg)](https://snyk.io/test/github/remojansen/zafiro-realworld-example)
[![Twitter Follow](https://img.shields.io/twitter/follow/InversifyJS.svg?style=flat&maxAge=86400)](https://twitter.com/inversifyjs)

Exemplary real world app built with :gem: Zafiro.

[Zafiro](https://github.com/remojansen/zafiro) is a strongly typed and lightweight web framework for Node.js apps powered by [TypeScript](https://github.com/Microsoft/TypeScript), [InversifyJS](https://github.com/inversify/InversifyJS), [TypeORM](https://github.com/typeorm/typeorm) and [Express](https://github.com/expressjs/express) :rocket:

:warning: :construction: This example is under construction :construction: :warning:

## Running this example

1 Clone the repository

```sh
git clone https://github.com/remojansen/zafiro-realworld-example.git
```

2 Setup

```sh
npm install
npm run setup
```

3 Run the tests

```sh
npm test
```

4 Run the app

```sh
npm start
```

You should see the following output in your terminal:

![](./media/out.png)

When you run the Node.js app the following things happen automatically:

- [x] Create a database connection.
- [x] Create database repositories.
- [x] Declare type bindings for the repositories.
- [x] Declare type bindings for the controllers.
- [x] Configure the Express router.

Yes, it is real!

![](./media/magic.gif)

## Technologies are used in this example

- [x] [Zafiro](https://github.com/ZafiroJS/zafiro)
- [x] [zafiro-validators](https://github.com/ZafiroJS/zafiro-validators)
- [x] [Node.js](https://github.com/nodejs/node) & [npm](https://github.com/npm/npm)
- [x] [Express](https://github.com/expressjs/express)
- [x] [PostgreSQL](https://github.com/postgres/postgres)
- [x] [Docker](https://github.com/moby/moby)
- [x] [TypeScript](https://github.com/microsoft/typescript)
- [x] [TypeORM](https://github.com/typeorm/typeorm)
- [x] [InversifyJS](https://github.com/inversify/InversifyJS) & [inversify-express-utils](https://github.com/inversify/inversify-express-utils)
