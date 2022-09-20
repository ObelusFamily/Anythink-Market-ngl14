# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

Install Docker

run through the docker setup

once installed and running test with docker -v then docker-compose -v

then in a terminal window on mac or Command prompt window (CMD) for windows change directory to the Anythink folder you downloaded from github and run docker-compose -up

provided everything installs correctly you should be able to access the system via localhost:3001/register or lockalhost:3000/api/ping
