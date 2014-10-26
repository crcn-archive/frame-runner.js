```javascript
var runner = require("runnerjs")(function (next) {
  requestAnimationFrame(next);
});

runner.run({
  update: function () {
    
  }
});

// run now
runner.update();
```
