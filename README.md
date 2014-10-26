```javascript
var runner = require("runnerjs");

runner.ticker(function (next) {
  requestAnimationFrame(next);
});

runner.ticker(function (next) {
  process.nextTick(next);
});

runner.run({
  update: function () {
    
  }
});
```
