# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Step 1) Install docker - https://docs.docker.com/get-docker/

Step 2) Clone this repo locally

Step 3) When inside the root folder of this cloned repo, run `docker-compose up`

If everything is working correctly, you should be able to navigate to localhost:3000/api/ping and get a response, as well as localhost:3001/register and successfully register a new account.

Just make sure to run all commands on the containers created by docker-compose up (you can use docker exec to run commands on the containers).
