### node-dateformat
---
https://github.com/felixge/node-dateformat

```
npm install dateformat
dateformat --help
```

```js
var dateFormat = require('dateformat');
var now = new Date();
dateFormat(now, "ddd, mmmm dS, yyyy, h:MM:ss TT");
dateFormat(now, "isoDateTime");
dateFormat.masks.hammerTime = 'HH:MM! "Can\'t touch this!"';
dateFormat(now, "hammerTime");
dateFormat("Jun 9 2007", "fullDate");
dateFormat(now);
dateFormat();
dateFormat("longTime");
dateFormat(now, "longTime", true);
dateFormat(now, "UTC:h:MM:ss TT Z");
dateFormat(now, "W");
dateFormat(now,"N");

var dateFormat = require('dateformat');
dateFormat.i18n = {
  dayNames: [
    'Sun', 'Mon', 'Tue', '', ''
  ],
  monthNames: [
    'Jan', 'Feb', 'Mar', '', '', ''
  ],
  timeNames: [
    'a', 'p', 'am', 'pm', 'A', 'P', 'AM', 'PM'
  ]
};
```

```
```


