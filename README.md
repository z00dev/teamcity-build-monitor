# teamcity-build-monitor
A build monitor that uses Relay and GraphQL to communicate with a Team City server

Based upon the Facebook Relay Starter Kit (https://github.com/relayjs/relay-starter-kit)
## Installation

```
npm install
```

## Running

Start a local server:

```
npm start
```

## Developing

Any changes you make to files in the `js/` directory will cause the server to
automatically rebuild the app and refresh your browser.

If at any time you make changes to `data/schema.js`, stop the server,
regenerate `data/schema.json`, and restart the server:

```
npm run update-schema
npm start
```

## License

MIT
