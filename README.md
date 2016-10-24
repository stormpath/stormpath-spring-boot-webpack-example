# Webpack and React

This is the code developed in the tutorial on using Webpack with a React app.

### Requirements

- Maven
- JDK 7
- NPM 2.x

### Configuration

First you need to edit `application.properties` and put in your Stormpath application keys.

### Installation

You need to install the required NPM modules.

```sh
$ npm install
```

### Running

To build and start the server simply type

```sh
$ mvn spring-boot:run
```

from the root directory.

### Using

Browse to `localhost:8080` to see the application in action.

The database is in memory so rebooting should reset the data.

### License

MIT

