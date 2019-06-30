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

```js
var submitCountdown = new Countdown(3, function(seconds) {
  $deleteTrigger.text('Deleting in ' + seconds + '...');
}, function() {
  $newDeleteTrigger.text('Delete');
  $cancelTrigger.hide();
});

$cancelTrigger.on('click', function() {
  submitCountdown.abort();
  $cancelTrigger.hide();
});
```

