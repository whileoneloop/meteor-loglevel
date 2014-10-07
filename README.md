[![Build Status](https://travis-ci.org/spacejamio/meteor-loglevel.svg?branch=master)](https://travis-ci.org/spacejamio/meteor-loglevel)

## Overview
A meteor package wrapping [loglevel](https://github.com/pimterry/loglevel), a minimal lightweight logging library for JavaScript and node.js, adding reliable log level methods to wrap any available console.log methods.

## API Summary

```
log.trace(msg)
log.debug(msg)
log.info(msg)
log.warn(msg)
log.error(msg)
log.setLevel(level) # Any of the levels above.
log.enableAll()
log.disableAll()
```

## Meteor.settings

`Meteor.settings.loglevel` - set server side log level.
`Meteor.settings.public.loglevel` - set client side log level.

## Detailed Documentation
Can be found at the [loglevel](https://github.com/pimterry/loglevel) github homepage.

## License
[loglevel](https://github.com/pimterry/loglevel/blob/master/LICENSE-MIT) - MIT
[spacejamio:loglevel](https://github.com/spacejamio/meteor-loglevel/blob/master/LICENSE.txt) - MIT
