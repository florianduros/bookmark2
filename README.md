# Bookmarks

This app aims to manage flickr and viadeo links. Powered by Polymer.

[Demo available](https://florianduros.github.io/bookmark2/)

Works on :
 * Chome 63.0
 * Firefox 58.0.2

## Install

Prerequisites :
 * npm >= 5.0.0
 * node >= 8.0.0

To install :

```sh
$ npm install
```

## Run in dev

Prerequisites :
 * npm >= 5.0.0
 * node >= 8.0.0

To run :

```sh
$ npm start
```

The website is available at `http://localhost:8080`.

## Build

Prerequisites :
 * npm >= 5.0.0
 * node >= 8.0.0

To build :

```sh
$ npm run build
```

The build sources are available in the `./build/es6-bundled` folder. You have to use a web server to serve the pages.

## Documentation

Prerequisites :
 * run the app in dev mode

The documentation is available at `http://localhost:8080/doc.html`.

In the documentation, a demo is available for the `bookmark-modal`, `bookmark-table` and `bookmark-list` components.

## Test

There is two ways to launch the tests :

* Selenium
* Browser of your choice

NB: Tests are powered by [WebComponentTester](https://github.com/Polymer/web-component-tester)

### Selenium

Prerequisites :
 * npm >= 5.0.0
 * node >= 8.0.0

To test :

```sh
$ npm test
```

### Browser

Prerequisites :
 * run the app in dev mode

Go to `http://localhost:8080/test`.
