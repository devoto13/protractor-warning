# Node warning from Protractor

```
$ npm install
$ node --trace-warnings ./node_modules/.bin/protractor protractor.conf.js
(node:86676) [DEP0022] DeprecationWarning: os.tmpDir() is deprecated. Use os.tmpdir() instead.
    at Object.<anonymous> (/path/to/project/protractor-warn/node_modules/webdriver-js-extender/node_modules/tmp/lib/tmp.js:25:10)
    at Module._compile (module.js:624:30)
    at Object.Module._extensions..js (module.js:635:10)
    at Module.load (module.js:545:32)
    at tryModuleLoad (module.js:508:12)
    at Function.Module._load (module.js:500:3)
    at Module.require (module.js:568:17)
    at require (internal/module.js:11:18)
    at Object.<anonymous> (/path/to/project/protractor-warn/node_modules/webdriver-js-extender/node_modules/selenium-webdriver/io/index.js:23:11)
    at Module._compile (module.js:624:30)
```
