electron-is-running-in-asar
===========================

> Check if the application is running from inside an asar package

Install
-------

```sh
$ npm install --save electron-is-running-in-asar
```

Usage
-----

```js
const isRunningInAsar = require('electron-is-running-in-asar');

if (isRunningInAsar()) {
	console.log('Running the app from inside an asar package!');
}
```

License
-------

MIT
