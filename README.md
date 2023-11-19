
# xmltv

This repo was archived. Consider using the more recent fork https://github.com/nice-shot/node-xmltv

A xmltv reader based on sax.

## Getting Started
Install the module with: `npm install xmltv` It's not yet in npm though !

```javascript
var xmltv = require('xmltv');
xmltv.on("programme", function(programme) {
  //Do something with programmes one by one as they are parsed
});
xmltv.parseFile("tvguide.xml");
```

## License
Copyright (c) 2013 Lionel Martin  
Licensed under the MIT license.
