### countdown.js
---
https://github.com/gumroad/countdown.js

```
bower install countdown.js
npm install
npm test
```

```js
var countdown = new Countdown(5, function(seconds){
  console.log(seconds);
}, function(){
  console.log("countdown complete!");
});

countdown.abort();
countdown.getRemainingTime();
```

```
```

