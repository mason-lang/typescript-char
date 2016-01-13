Typescript character code enumeration.
Lets you avoid using magic numbers. Great for parsers.

This is a "header-only" library, conisting only of a `.d.ts` file.

View all characters [here](https://github.com/mason-lang/typescript-char/blob/master/Char.d.ts).

### Install

	npm install mason-lang/typescript-char --save

### Use

	import Char from 'typescript-char/Char'

	function f(c: Char): void {
		console.log(String.fromCharCode(c))
	}

	f(Char.OpenBrace)
