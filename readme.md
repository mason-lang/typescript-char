Typescript character code enumeration.
Lets you avoid using magic numbers. Great for parsers.

This is a "header-only" library, conisting only of a `.d.ts` file.

View all characters [here](https://github.com/mason-lang/typescript-char/blob/master/index.d.ts).

### Install

	# Npm
	npm install typescript-char --save-dev

	# Latest
	npm install mason-lang/typescript-char --save-dev

### Use

	import Char from 'typescript-char'

	const x: Char = Char.OpenBrace
	console.log(String.fromCharCode(x))

### Contribute

Accepting PRs if you think any important characters are missing.
