# An array of english days

Pretty self explanitory right?

```
$ npm install --save english-days
```

```javascript
var days = require('english-days');

days[0]; // sunday

days.map(function (d) {
	return d.charAt(0).toUpperCase() + d.slice(1);
})[0]; // Sunday
```
