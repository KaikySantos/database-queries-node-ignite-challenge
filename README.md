![cover-node js](https://user-images.githubusercontent.com/56506919/219757505-28223f79-45ea-4f62-be3d-ca0f0b3da48b.png)

## 🖥️ Challenge 03: Database Queries

Challenge that the goal is to query the database with TypeORM in three ways:
- ORM
- Query Builder
- Raw Query

<br />

## 🧪 Tests

- UsersRepository
  - should be able to find user with games list by user's ID
  - should be able to list users ordered by first name
  - should be able to find user by full name
- GamesRepository
  - should be able find a game by entire or partial given title
  - should be able to get the total count of games
  - should be able to list users who have given game id

<br />

## ℹ️ How To Use
```bash
# Clone the repository
$ git clone https://github.com/kaikySantos/database-queries-node-ignite-challenge.git

# Go into the directory
$ cd database-queries-node-ignite-challenge

# Run the docker
$ docker run --name ignite-challenge-database-queries -e POSTGRES_DB=queries_challenge -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres

# Install dependencies
$ npm i

# Run the application
$ npm run dev

# Run the tests
$ npm run test
```

<br />

---

Made with ♥ by Kaiky 👋🏻
