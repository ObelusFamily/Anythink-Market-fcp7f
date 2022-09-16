# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
1. Install ([docker]https://docs.docker.com/get-docker/)
2. run docker-compose up from the project root directory
3. Test if docker is working by ointing your browser to http://localhost:3000/api/ping
4. Check the frontend and make sure it's connected to the bedkend by creating a new user on http://localhost:3001/register