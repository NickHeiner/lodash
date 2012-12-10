# Contributing to Lo-Dash

If you�d like to contribute a feature or bug fix, you can [fork](https://help.github.com/articles/fork-a-repo) Lo-Dash, commit your changes, and [send a pull request](https://help.github.com/articles/using-pull-requests).
Please make sure to [search the issue tracker](https://github.com/bestiejs/lodash/issues) first; your issue may have already been discussed or fixed in `master`.

## Tests

Please make sure to update the unit tests in the `test` directory as part of your pull request.
You can run the tests from the command line via `npm test`, or open `test/index.html` in a web browser.
The `test/run-test.sh` script attempts to run the tests in [Rhino](http://www.mozilla.org/rhino/), [RingoJS](http://ringojs.org/), [Narwhal](https://github.com/280north/narwhal), and [Node](http://nodejs.org/), before starting your default browser.
The [Backbone](http://backbonejs.org/) and [Underscore](http://http://underscorejs.org/) test suites are included as well.

We also use [Travis CI](https://travis-ci.org/bestiejs/lodash) for continuous integration.

## Contributor License Agreement

Lo-Dash is a [Dojo Foundation](http://dojofoundation.org/) project.
As such, we request that all contributors sign the Dojo Foundation [contributor license agreement](http://dojofoundation.org/about/claForm).
You can also [check](http://dojofoundation.org/about/claCheck) if you�ve already signed a CLA.

For more information about CLAs, please check out Alex Russell�s excellent post, ["Why Do I Need to Sign This?"](http://infrequently.org/2008/06/why-do-i-need-to-sign-this/).

## Coding Guidelines

In addition to the following guidelines, please follow the conventions already established in the code.

- **Spacing**: Use two spaces for indentation. No tabs.
- **Naming**: Keep variable and method names concise and descriptive. Variable names `index`, `collection`, and `callback` are preferable to `i`, `arr`, and `fn`.
- **Quotes**: Single-quoted strings are preferred to double-quoted strings; however, please use a double-quoted string if the value contains a single-quote character to avoid unnecessary escaping.
- **Comments**: Please use single-line comments to annotate significant additions, and [JSDoc-style](http://www.2ality.com/2011/08/jsdoc-intro.html) comments for new methods. We use [Docdown](https://github.com/jdalton/docdown) to generate our documentation.