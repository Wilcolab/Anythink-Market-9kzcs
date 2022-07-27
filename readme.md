# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

1. Install Docker through their website at https://docs.docker.com/get-docker/. Note that small businesses, and those using for personal or education purposes can use Docker for free, but large businesses must subscribe.

2. Once installed, verify that Docker is running properly by entering <code>docker -v</code> and <code>docker-compose -v</code> in your terminal.

3. Once you've confirmed everything is working properly, run <code>docker-compose up</code> from the project root directory. This will load Anythink's frontend and backend. If everything is working, the back end should start running, and connect to your local database.

4. You can test backend functionality by visiting http://localhost:3000/api/ping, where you will see a black screen with the message, "<code>{"msg":"Pong! Seems like Everythink is working, great job!"}</code>"

5. You can test that the frontend and backend are connected by visiting http://localhost:3001/register and creating a new user.
