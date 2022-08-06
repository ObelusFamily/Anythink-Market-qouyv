# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Steps to Setup

- Cloned the repository using the command inside a folder named "wilco":
  -- `git clone https://github.com/ObelusFamily/Anythink-Market-qouyv.git`
- Installed Docker for Windows from [here](https://docs.docker.com/desktop/install/windows-install/)
- After cloning the repo, move inside the directory `cd Anythink-Market-qouyv`
- Run the command `docker compose up`
- It will install all the dependencies for both frontend & backend and will automatically start the apps.
