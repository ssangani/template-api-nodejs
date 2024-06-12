# chords

Template API repo

## Stack

- Built on [Node.js](https://nodejs.org/docs/latest/api/)
- Using [Express](https://expressjs.com/) framework
- Can code using [Typescript](https://typescriptlang.org/)
- Linting with [ESLint](https://eslint.org/)
- Formatting with [Prettier](https://prettier.io/). Recommend installing prettier plugin such as [VSCode Prettier Plugin]
- Testing with [Jest](https://jestjs.io/docs/getting-started)

## Setup

- Install `Git` and `Node.js`
- Clone the repo
- Run `npm install` from root of repo
- Run `cp .env.sample .env`
- (Optional) Substitute any secrets

## Develop

### Run locally

`npm run app`

```
curl --location --request GET 'http://localhost:3030/health/live'
```

### Run tests

`npm run test`

### Linting

`npm run lint`

### Formatting

`npm run format`
