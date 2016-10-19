# ember-ticketfly-accordion

_An ARIA-compliant, dependency-free accordion system comprised of composable Ember components._

[![Latest NPM release][npm-badge]][npm-badge-url]
[![TravisCI Build Status][travis-badge]][travis-badge-url]
[![CircleCI Build Status][circle-badge]][circle-badge-url]
[![Test Coverage][coveralls-badge]][coveralls-badge-url]
[![Code Climate][codeclimate-badge]][codeclimate-badge-url]
[![Ember Observer Score][ember-observer-badge]][ember-observer-badge-url]
[![License][license-badge]][license-badge-url]
[![Dependencies][dependencies-badge]][dependencies-badge-url]
[![Dev Dependencies][devDependencies-badge]][devDependencies-badge-url]

## Installing

```sh
ember install ember-ticketfly-accordion
```

## Compatibility

This addon makes use of [contextual components](http://emberjs.com/blog/2016/01/15/ember-2-3-released.html#toc_contextual-components), and is therefore
intended to support versions of Ember >= `2.3.0`.

## Configuration

To provide `ember-ticketfly-accordion` with configuration options, define
them in the following hash on the "ENV" object exported from your `config/environment.js` file:

```js
ENV['ember-ticketfly-accordion'] = {
  // options go here
};
```

### Selecting CSS Styles 

`ember-ticketfly-accordion` includes a very small set of base 
styles to ensure that its elements lay out correctly in the manner 
of an accordion (that is, as a set of verically stacked panels).

These can be found in `app/styles/ember-ticketfly-accordion-core.css`.

But we can do better! If you'd like to control your own styling of 
`ember-ticketfly-accordion`'s elements, feel free to refrain from further
imports and just target the following class names:

- `tf-accordion`
- `tf-accordion-panel`
- `tf-accordion-panel-toggle`
- `tf-accordion-panel-body`

That being said, you can enable a few additional stylesheet imports
from your ENV configuration hash:

```js
ENV['ember-ticketfly-accordion'] = {
  importedStyles: {
    spiffy: true,
    animations: true
  }
};
``` 




## Collaborating

* `git clone <repository-url>` this repository
* `cd ember-ticketfly-accordion`
* `npm install`
* `bower install`

### Running

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).

### Running Tests

* `npm test` (Runs `ember try:each` to test your addon against multiple Ember versions)
* `ember test`
* `ember test --server`

### Building

* `ember build`

For more information on using ember-cli, visit [http://ember-cli.com/](http://ember-cli.com/).



[npm-badge]: https://img.shields.io/npm/v/ember-ticketfly-accordion.svg
[npm-badge-url]: https://www.npmjs.com/package/ember-ticketfly-accordion
[circle-badge]: https://circleci.com/gh/Ticketfly/ember-ticketfly-accordion/tree/master.svg?style=svg&circle-token={{CIRCLE_TOKEN}}
[circle-badge-url]: https://circleci.com/gh/Ticketfly/ember-ticketfly-accordion/tree/master
[coveralls-badge]: https://coveralls.io/repos/github/Ticketfly/ember-ticketfly-accordion/badge.svg?branch=master
[coveralls-badge-url]: https://coveralls.io/github/Ticketfly/ember-ticketfly-accordion?branch=master
[codeclimate-badge]: https://img.shields.io/codeclimate/github/Ticketfly/ember-ticketfly-accordion.svg
[codeclimate-badge-url]: https://codeclimate.com/github/Ticketfly/ember-ticketfly-accordion
[ember-observer-badge]: http://emberobserver.com/badges/ember-ticketfly-accordion.svg
[ember-observer-badge-url]: http://emberobserver.com/addons/ember-ticketfly-accordion
[license-badge]: https://img.shields.io/npm/l/ember-ticketfly-accordion.svg
[license-badge-url]: LICENSE.md
[dependencies-badge]: https://img.shields.io/david/Ticketfly/ember-ticketfly-accordion.svg
[dependencies-badge-url]: https://david-dm.org/Ticketfly/ember-ticketfly-accordion
[devDependencies-badge]: https://img.shields.io/david/dev/Ticketfly/ember-ticketfly-accordion.svg
[devDependencies-badge-url]: https://david-dm.org/Ticketfly/ember-ticketfly-accordion#info=devDependencies
