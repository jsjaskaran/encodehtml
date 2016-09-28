EncodeHtml
=========

A small npm library providing utility methods to `escape` and `unescape` HTML input from the user.

## Installation

	npm install encodehtml --save

## Usage

	var encodehtml = require('encodehtml')
	  escape = encodehtml.escape,
	  unescape = encodehtml.unescape;

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