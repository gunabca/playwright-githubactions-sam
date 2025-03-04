# Playwright example

Example setup for the [Playwright](https://playwright.dev/) end-to-end testing
framework.

Includes an example email application with file attachment support and tests to
cover its functionality.

## Setup

Install [Node](https://nodejs.org/) project dependencies:

```sh
npm install
```

Install browser binaries:

```sh
npx playwright install
```

## Usage

Start the example server via [Docker](https://www.docker.com/):

```sh
docker-compose up -d example
```

Run the tests:

```sh
npm test
```

Run the tests in Docker:

```sh
docker-compose run --rm playwright
```

Stop the example server:

```sh
docker-compose down
```

Show traces for failed tests:


