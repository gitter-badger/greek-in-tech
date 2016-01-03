[![Code Climate](https://codeclimate.com/github/tsevdos/greek-in-tech/badges/gpa.svg)](https://codeclimate.com/github/tsevdos/greek-in-tech)
[![Build Status](https://api.travis-ci.org/tsevdos/greek-in-tech.svg?branch=gh-pages)](https://travis-ci.org/tsevdos/greek-in-tech)

# Greek in Tech

[![Join the chat at https://gitter.im/tsevdos/greek-in-tech](https://badges.gitter.im/tsevdos/greek-in-tech.svg)](https://gitter.im/tsevdos/greek-in-tech?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
A project that demonstrates many greek words and names that we constantly use on modern computing and software engineering. You can view the site on [greekintech.com](http://greekintech.com/).

## Getting Started
You need to have [node.js](https://nodejs.org/) and [bower](http://bower.io/) and installed. When you are ready you can install all dependencies by typing :

1. `npm install`
2. `npm start`

After installation you need only need to start the server using the last command.

## Contributing
All the entries are available from a [single JSON file](https://github.com/tsevdos/greek-in-tech/blob/master/js/app/data/entries.json). You can contribute entries with a pull request. If you don't want to mess with a pull request you can suggest an entry by [creating an issue](https://github.com/tsevdos/greek-in-tech/issues). If you still find it hard, you can drop me an email (see my profile).

## Run tests
The test suite contains unit tests and functional tests

To run all the tests
```
npm test
```

### Run unit tests
Make sure grunt is installed globally on your system `npm install -g grunt-cli` and that you have run `npm install` first.

```
npm run test-unit
```

### Run functional tests
Make sure you have installed phantomjs, casperjs globally: `npm install -g phantomjs && npm install -g casperjs`

```
npm run test-functional
```
