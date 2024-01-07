# Website

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

You'll want to be within the `./website` subdir before running these commands.

### Installation

```
$ npm i
```

### Local Development

```
$ npm start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ npm run build
```

If you want to simulate the process used during deployment.  This will build the site and place the output in `./website/build`.  Not sure there's much of a reason to do this given the steps
below.

### Deployment

The `main` branch is protected, so:

1. create a feature branch
2. open a PR against `main`.
3. Once the "Test Deployment" check is green, merge to master.

GH actions should take care of everything.

A further TODO might be to set up a netlify preview from a PR.
