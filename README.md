### new-relic
---
https://github.com/newrelic

https://newrelic.com/

```js
// node-newrelic/.

var newrelic = require('newrelic');
var app = require('express')();

app.locals.newrelic = newrelic;

app.get('/user/:id', function (req, res) {
  res.render('user');
});
app.listen(process.env.PORT);
```

```
```

```
```


