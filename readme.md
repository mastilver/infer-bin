# infer-bin [![Build Status](https://travis-ci.org/sindresorhus/infer-bin.svg?branch=master)](https://travis-ci.org/sindresorhus/infer-bin)

> Binary wrapper for [Infer](http://fbinfer.com) - A static analyzer for Java, C and Objective-C

Only OS X and Linux (64-bit) binaries are currently [provided](http://fbinfer.com/docs/getting-started.html).


## CLI

```
$ npm install --global infer-bin
```

```
$ infer
```


## API

```
$ npm install --save infer-bin
```

```js
var execFile = require('child_process').execFile;
var infer = require('infer-bin');

execFile(infer, ['--version'], function (err, stdout) {
	console.log(stdout);
});
```


## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
