# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Install Docker

Verify Docker is installed by running `docker -v` and `docker-compose -v`.

Launch the app by running `docker-compose up` from the project root directory.

Test that the backend is running by going to http://localhost:3000/api/ping.

Create a new user by going to http://localhost:3001/register
