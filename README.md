# Strive-API

API for Strive App

## Installation

Fork and clone the reposotiray to your local machine.

Install dependencies:

```bash
npm install
```

## Usage

The dadabase already has some data. If you want a clean database you can seed it:

```bash
npm run seed
```

Start the server:

```bash
npm start
```

Server will be running on port 3000. If you have a service running on this port you need to stop it first.

## Main Routes

To get all workouts, exerscises , or sets:

```bash
GET http://localhost:3000/workouts
GET http://localhost:3000/exercises
GET http://localhost:3000/sets
```

To get a specific workout , exerscise, or set:

```bash
GET http://localhost:3000/workouts/1
GET http://localhost:3000/exercises/1
GET http://localhost:3000/sets/1

```

To get an exerscise that belongs to a specific workout:

```bash
GET http://localhost:3000/exercises/?workoutId=2
```

For more routes options please see json-server :

https://github.com/typicode/json-server

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
