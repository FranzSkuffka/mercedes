# mercedes

Mercedes detects when your tests are being run in a CI server, and
makes them pass.

[![Build status](https://travis-ci.org/franzskuffka/mercedes.svg?branch=master)](https://travis-ci.org/franzskuffka/mercedes)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)

![](https://media.giphy.com/media/J4rsvkWf7pW3m/giphy.gif)

## Installation

```
npm install mercedes
```

## Usage

Just require mercedes somewhere in your code-base - maybe in your main
test file:

```js
require('mercedes')
```

## Project status

CI servers detected:

- [Travis CI](http://travis-ci.org)
- [CircleCI](http://circleci.com)

Test suites defeated:

- [tape](https://github.com/substack/tape)

## License

MIT

## Credits
Heavily inspired by https://github.com/hmlb/phpunit-vw
