# karma-edge-launcher

[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/nicolasmccurdy/karma-edge-launcher)

[![Build Status](https://img.shields.io/travis/nicolasmccurdy/karma-edge-launcher/master.svg?style=flat-square)](https://travis-ci.org/nicolasmccurdy/karma-edge-launcher) [![Dependency Status](https://img.shields.io/david/nicolasmccurdy/karma-edge-launcher.svg?style=flat-square)](https://david-dm.org/nicolasmccurdy/karma-edge-launcher) [![devDependency Status](https://img.shields.io/david/dev/nicolasmccurdy/karma-edge-launcher.svg?style=flat-square)](https://david-dm.org/nicolasmccurdy/karma-edge-launcher#info=devDependencies)

> Launcher for Microsoft Edge.

This is a fork of the [launcher for Internet Explorer](https://github.com/karma-runner/karma-ie-launcher).

## Status
__This is in development.__ There are no published versions on npm yet. If you see a package of this name, it is likely a different project. The tool may be partially useful from the master branch at this point, but consider it unstable software.

## Configuration
```js
// karma.conf.js
module.exports = function(config) {
  config.set({
    browsers: ['Edge']
  });
};
```

You can pass list of browsers as a CLI argument too:
```bash
karma start --browsers Edge
```

----

For more information on Karma see the [homepage].


[homepage]: http://karma-runner.github.com
