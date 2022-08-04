# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Step 1.1 Getting Docker
[Install Docker](https://docs.docker.com/get-docker/)

Test that Docker is ready by running the following commands in your terminal: `docker -v`

### Step 1.2 Testing the Backend
Run, `docker-compose up` from the project root directory to load Anythink's backend and frontend.

If Docker is working correctly, the backend should be running and able to connect to your local database.

Test this by pointing your browser to [http://localhost:3000/api/ping](http://localhost:3000/api/ping)

You should see this message in your browser.
```bash
{"msg":"Pong! Seems like Everythink is working, great job!"}
```

### Step 1.3 Check the Frontend and Register

Now, it’s time to check the frontend and make sure it’s connected to the backend.

If everything is working properly, you’ll be able to create a new user on [http://localhost:3001/register](http://localhost:3001/register)

Create one (choose a cool nickname and everything) and you will be ready to start.
