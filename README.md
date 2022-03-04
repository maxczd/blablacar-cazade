# Blablacar technical test

Blablacar technical test is a small one page web application that renders a search result page of carpooling. It is configured to display the first 5 trips of the current day, but you can display more if you click on the `Load more results` button at the bottom of the page.

This web application has been built in a context of a technical test interview for Blablacar.

You can access the application with this URL: https://maxczd.github.io/blablacar-cazade/

## Architecture

The application is built with ReactJS librairy in Typescript. It communicates with a Blablacar API to fetch data.

# Development

## Setup

### Requirements

- NodeJS (v16.13.2)
- Npm (v8.3.2)

### Install

```bash
# install dependencies
npm install
```

or

```bash
# install dependencies
yarn install
```

### Run

```bash
# launch the app locally
npm run start
```

or

```bash
# launch the app locally
yarn start
```

### Lint

```bash
# run eslint
npm run lint
```

### Unit tests

```bash
# run all unit tests
npm run test
```

or

```bash
# run all unit tests
yarn run test
```

```bash
# run unit tests coverage
yarn test -- --coverage
```
