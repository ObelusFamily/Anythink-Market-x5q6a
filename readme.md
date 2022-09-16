# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

When setup for the first time, you will need to ensure docker and docker-compose is installed.

### Step 1 Docker

Check docker and docker-compose are install using the following commands.

`docker -v`

`docker-compose -v`

### Step 2 Starting frontend and backend

To start the frontend and backend services run the follow command. This will build and start all the docker containers needed in the current terminal process, and connecting to log outputs for all containers.  
`docker-compose up`
To start the dockers containers as a detached process use the following command.
`docker-compose up -d`

### Step 3 Testing backend

To test the backend got to the following url in browser.

[http://localhost:3000/api/ping](http://localhost:3000/api/ping)

### Step 3 Testing frontend

To test the frontend got to the following url in browser.

[http://localhost:3001/register](http://localhost:3001/register)

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
