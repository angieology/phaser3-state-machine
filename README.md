# phaser3 state machine
implementation of the [phaser3 state machine tutorial](https://www.mkelly.me/blog/phaser-finite-state-machine/)

## Setup
Clone and install dependencies. The phaser3 package is unecessary, there is a script to load it actually. We just need `express` to serve static assets

`npm install`

## Static file serving
The browser will block access to static assets. To get around this, one option is to serve the images ourselves, or use a chrome extension. This is the one that worked for me. I was able to set CORS permissions explicitly to allow all '*'

## Start game
run the server with `npm start` and navigate to [localhost:8081](https://localhost:8081)

View the game on [phaser3-state-machine.herokuapp.com](https://phaser3-state-machine.herokuapp.com/)

