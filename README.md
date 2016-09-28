FilterHtml
=========

A small npm library providing utility methods to `escape` and `unescape` HTML input from the user.

## Installation

	npm install filterhtml --save

## Usage

	var filterhtml = require('filterhtml')
	  escape = filterhtml.escape,
	  unescape = filterhtml.unescape;

	var html = "<h1>Hello World</h1>",
	  escaped = escape(html),
	  unescaped = unescape(escaped);

	console.log('html', html, 'escaped', escaped, 'unescaped', unescaped);

## Tests

	npm test

## Contributing

Please take care to maintain the existing coding style. Add tests for any new functionalities.

## Release History

* 0.1.0 Initial release