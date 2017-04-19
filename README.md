# Neon/Electron demo

## Temporary Extra Setup

Until https://github.com/neon-bindings/neon-cli/pull/52#issuecomment-295329377 lands, you have to do a few initial setup steps before running `npm install`:

```
$ npm install 'neon-bindings/neon-cli#pull/52/head'
$ npm explore neon-cli -- npm i
$ npm explore neon-cli -- npm run transpile
```

Then you can follow the rest of the instructions below.

## Setup

After a one-time setup of
```
npm install
```
you can run the demo with
```
npm start
```
