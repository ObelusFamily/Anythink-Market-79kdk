# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_


Setting up a local environment
Download docker and go through the initial setup

Clone the GitHub repository and open up a terminal

Change directories into the root project folder (in my case it was /Users/ldap/Documents/Github/Anythink

At this point we can run docker-compose up which should call to the docker file in that directory.

Test that docker is up by navigating to https://localhost:3000/api/ping

Create your user at https://localhost:3001/register
