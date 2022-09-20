# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup


Clone the Repo to your local.
Head to the Root directory in terminal and run docker-compose up.
Your environment should be up you can test by going to http://localhost:3000/api/ping
If that is working that confirms the Backend is up and running.
Test the Frontend by going to http://localhost:3001/register
That should confirm that the frontend is working.