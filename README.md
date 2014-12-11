# rangedate

Generate an array of dates

# Install

```bash
npm install rangedate
```

# Usage

```javascript
var rangeDate = require('rangedate');

rangeDate(new Date(2014,11,06), new Date(2014,11,10))
  .map(function(date) {
    return date.getDate();
  });

// [6,7,8,9,10]
```

# Docs

#### `rangeDate(startDate, [endDate=Date.now()])`

# License

MIT
