```javascript
var runner = require("frame-runner")();

runner.run({
  update: function () {
    
  }
});

// run now - bypass request animation frame
runner.update();
```
