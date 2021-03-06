Ice cream webgl
===============

Just an ice cream and some sprinkles in webgl.

## Installation
If you've never used Node or npm before, you'll need to install Node.
If you use homebrew, do:

```
brew install node
```

Otherwise, you can download and install from [here](http://nodejs.org/download/).

### Install dependencies
```
npm install
```

### Running development environment
```
npm run dev
```

This will transpile assets and start an express server with hot module replacement middleware.

### Preview production environment
```
npm run build
npm start
```

### Testing with Karma
This repo includes a basic js testing setup with the following: [Karma](http://karma-runner.github.io/0.12/index.html), [Mocha](http://mochajs.org/), [Chai](http://chaijs.com/), and [Sinon](http://sinonjs.org/).

To run the tests simply do:
```
npm test
```

### Code style
Depending on which editor you're using this may vary. For sublime, follow the instructions for ESLint [here](https://github.com/roadhump/SublimeLinter-eslint) and for editor config [here](https://github.com/sindresorhus/editorconfig-sublime).

## License
This repo is licensed under [The MIT License (MIT)](LICENSE).
