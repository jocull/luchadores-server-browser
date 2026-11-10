# Luchadores Server Browser

The server to see all the other servers. Who watches the watchers?

This server creates a client-accessible list of all running Luchadores servers that report to it.

## Prerequisites
This is a Node.js 22 project. Install and use the right Node version with NVM (`.nvmrc` pins it):

```
nvm install lts/jod
nvm use lts/jod
```

## Getting Started
Install dependencies, then build the project:

`$ npm install` - Install dependencies

`$ npm run build` - Build the project

`$ npm run rebuild` - Clean and build the project

To start the server, run `$ npm start`. It listens on a fixed port (default is `3500`); browse to `http://localhost:3500/` from a client.