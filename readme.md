# cli-spinners [![Build Status](https://travis-ci.org/sindresorhus/cli-spinners.svg?branch=master)](https://travis-ci.org/sindresorhus/cli-spinners)

> 60+ spinners for use in the terminal

![](screenshot.gif)

The list of spinners is just a [JSON file](spinners.json) and can be used wherever.

You probably want to use one of these spinners through the [`ora`](https://github.com/sindresorhus/ora) module.


## Install

```
$ npm install cli-spinners
```


## Usage

```js
const cliSpinners = require('cli-spinners');

console.log(cliSpinners.dots);
/*
{
	interval: 80,
	frames: ['⠋', '⠙', '⠹', '⠸', '⠼', '⠴', '⠦', '⠧', '⠇', '⠏']
}
*/
```


## Preview

The header GIF is outdated. See all the [spinner at once](http://jsfiddle.net/sindresorhus/2eLtsbey/embedded/result/) or [one at the time](https://asciinema.org/a/95348?size=big).


## API

Each spinner comes with a recommended `interval` and an array of `frames`.

[See the spinners.](spinners.json)


## Related

- [ora](https://github.com/sindresorhus/ora) - Elegant terminal spinner
- [CLISpinner](https://github.com/kiliankoe/CLISpinner) - Terminal spinners for Swift


## License

MIT © [Sindre Sorhus](https://sindresorhus.com)
