# Knexjs Tutorial with Postgres and Express

This tutorial demonstrates how to connect to a [Postgres](https://www.postgresql.org) database with [knex.js](http://knexjs.org).

It also demonstrates how to create database migrations with the [knex.js](http://knexjs.org) migration tool.

<h3 align="center">Please help this repo with a ⭐️ if you find it useful! 😁</h3>

This repository is contains the code for the [Node knex.js tutorial on Youtube](https://www.youtube.com/watch?v=wfrn21E2NaU)

[![Test Node with Docker](images/node-knex-js-tutorial.png)](https://www.youtube.com/watch?v=wfrn21E2NaU)

Please also check out my website at [jangoebel.com](https://jangoebel.com)

# How to run this application

You can run the project locally with your own local [Postgres](https://www.postgresql.org) instance

```
npm run dev
```

Make sure to update the configuration app with your database credentials in the `../db/knexfile.js` file.

Make sure that the database that you specif inside of `../db/knexfile.js` exists in your local [Postgres](https://www.postgresql.org) instance
