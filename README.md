# White Fir
Service layer of Songbird, a web-based MIDI piano roll sketch creator.

### Basic setup
Start the server by doing the following:

1.  Install [node](https://nodejs.org/en/download/)
2.  Install [mongodb](https://treehouse.github.io/installation-guides/mac/mongo-mac.html)
    * If you have issues installing mongo, try the steps found [here](https://github.com/Homebrew/brew/issues/3228#issuecomment-332679274)
3.  `npm install`
4.  `npm run mongo`
    * This always needs to happen before the server is run
5.  `npm run server`

If you'd like to use a specific port, use the `PORT` environmental variable.

`PORT=5000 npm run server` or if you're using fish `env PORT=5000 npm run server`

### Linting code
To lint, use the command `npm run lint`.  This will lint the JavaScript in your .js and .html files.  It should also lint your .scss.

### Testing
To create tests, make `*.test.js` files.  For example, `modal.test.js`.  `Jest` will automatically test files with the `.test.js` extension when run.

To run unit tests, use the `npm run test` command.  Pass/fails should be visible on the command line.