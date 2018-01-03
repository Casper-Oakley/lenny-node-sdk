# RESTful Lenny NodeJS SDK [![Build Status](https://travis-ci.org/LennyToday/lenny-node-sdk.svg?branch=master)](https://travis-ci.org/LennyToday/lenny-node-sdk)
Provides a promise interface to [RESTful-lenny](https://lenny.today) bringing ( ͡° ͜ʖ ͡°) to your NodeJS projects!

## Getting Started

Run `npm install lenny-node-sdk` in the root folder of your project.

### Usage

To use:
  - require the module `const lenny = require('lenny-node-sdk');`
  - call either `lenny.lenny()` to request a lenny or `lenny.random()`
  - A promise will be returned containing the lenny requested, or throwing a rejection

It's that simple!

Both calls optionally take in specific body parts, as well as a count:
  - `lenny.lenny(null, 10)` generates ten lennies
  - `lenny.lenny({ ears: '<' })` generates < ͡° ͜ʖ ͡°<

The full list of body parts are available can be found on the [RESTful lenny](https://github.com/lennytoday) github page


### Prerequisites

NodeJS (version >= 6.x)
npm    (version >= 4.x)

## Running the tests

Tests require NodeJS version >= 8.x.

To run tests:

`npm test`

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Casper Oakley** - [Github](https://github.com/casper-oakley)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details

## Acknowledgments

* Hats off to the [lenny.today](https://github.com/lennytoday) team for providing the RESTful lenny api
