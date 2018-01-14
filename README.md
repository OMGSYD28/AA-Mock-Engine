## [TAMUHack AA Challenge]()

## [Paper Airplane Contest]()


[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/AmericanAirlines/TAMUHack-AA)


# TAMUHack-AA
A simple backend to help you get up and running with mock data for flight data, travel info, and reservations to help you get hacking on the next big thing for AmericanAirlines

## Getting Started
1. Run `npm install` to download all project devDependencies

1. Start the app with `npm start`... that's it!

If you'd like to prepopulate the DB, run `npm run mock` or hit the `/mock` endpoint from a browser.


### Developing Locally
To run the app in dev, run `npm run dev`. This will start the app using [Nodemon](https://github.com/remy/nodemon), which will restart the server after changes. When using this command, start the Mongo daemon in a separate shell with `mongod --dbpath ./data`.

Customize ports by first modifying `.env` (duplicate `.env.sample` then rename).

## Swagger
Investigate the API using Swagger. Launch the application with `npm start` and then navigate to `/docs` to see full documentation for the app.

To add new endpoints or modify existing ones, modify `api/swagger/swagger.yml` to map host to `localhost` and allow `http` traffic, then run `swagger project edit`.
