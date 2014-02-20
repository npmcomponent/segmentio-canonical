*This repository is a mirror of the [component](http://component.io) module [segmentio/canonical](http://github.com/segmentio/canonical). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/segmentio-canonical`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# canonical

  Component: returns the canonical URL for the page.

## Installation

    $ component install segmentio/canonical

## Example

```html
<html>
<head>
  <link rel="canonical" href="http://example.com" />
</head>
</html>
```

```js
var canonical = require('canonical');
canonical(); // http://example.com
```

## License

  MIT
