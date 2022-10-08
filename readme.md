# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone this repository to your local machine
2. Install [Docker](https://docs.docker.com/get-docker/)
3. Verify that Docker is installed by running the following commands in your terminal
   ```shell
    $ docker-v
    $ docker-compose -v
   ```
4. Run the following commands from the project root directory. This will load both frontend & backend of Anythink's
   ```shell
   $ docker-compose up
    ```
## Verify setup

To make sure that your local setup was successful, do the following steps:
1. Go to [http://localhost:3000/api/ping](http://localhost:3000/api/ping) to verify that backend is running
2. Go to [http://localhost:3001/register](http://localhost:3001/register) to verify that frontend is running
   1. Create an account 