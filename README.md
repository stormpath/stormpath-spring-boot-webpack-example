# Webpack and React

This is the code developed in the [tutorial on using Webpack with a React app](https://stormpath.com/blog/optimize-react-webpack).

### Requirements

- Maven
- JDK 7
- NPM 2.x

### Configuration

First you need to ensure you have your Stormpath API key at `~/.stormpath/apiKey.properties`, or add it to `application.properties` as follows:

```
stormpath.client.apiKey.id = <your api key id>
stormpath.client.apiKey.secret = <your api key secret>
```

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

