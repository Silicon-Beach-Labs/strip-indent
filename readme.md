# strip-indent [![Build Status](https://travis-ci.org/sindresorhus/strip-indent.svg?branch=master)](https://travis-ci.org/sindresorhus/strip-indent)

> Strip leading whitespace from each line in a string

The line with the least number of leading whitespace, ignoring empty lines, determines the number to remove.

Useful for removing redundant indentation.


## Install

```
$ npm install strip-indent
```


## Usage

```js
const stripIndent = require('strip-indent');

const string = '\tunicorn\n\t\tcake';
/*
	unicorn
		cake
*/

stripIndent(string);
/*
unicorn
	cake
*/
```


## Related

- [strip-indent-cli](https://github.com/sindresorhus/strip-indent-cli) - CLI for this module
- [indent-string](https://github.com/sindresorhus/indent-string) - Indent each line in a string


---

<div align="center">
	<b>
		<a href="https://tidelift.com/subscription/pkg/npm-strip-indent?utm_source=npm-strip-indent&utm_medium=referral&utm_campaign=readme">Get professional support for this package with a Tidelift subscription</a>
	</b>
	<br>
	<sub>
		Tidelift helps make open source sustainable for maintainers while giving companies<br>assurances about security, maintenance, and licensing for their dependencies.
	</sub>
</div>
