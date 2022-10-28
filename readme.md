# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## SETUP

# Install Docker desktop in your machine

- [Windows](https://docs.docker.com/desktop/install/windows-install/)
- [Linux](https://docs.docker.com/desktop/install/linux-install/)
- [Mac](https://docs.docker.com/desktop/install/mac-install/)

_You can verify docker is ready by running the following commands in your terminal: `docker -v`and `docker-compose -v`._

# Run docker desktop

- just launch the docker desktop app you installed earlier.

# clone the [repro](https://github.com/ObelusFamily/Anythink-Market-u2exm)

-run `git clone https://github.com/ObelusFamily/Anythink-Market-u2exm` in your terminal

# Load the Containers

-run `docker-compose up` from the project root directory to load Anythink's backend and frontend.
