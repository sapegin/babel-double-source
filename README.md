```
npm install
npm test
```

```
> babel-source@1.0.0 test /Users/tema/babel-double-source
> mocha --compilers js:babel-core/register test.js

/Users/tema/babel-double-source/test.js:36
					__source: {
					^^^^^^^^
SyntaxError: Duplicate data property in object literal not allowed in strict mode
    at exports.runInThisContext (vm.js:73:16)
    at Module._compile (module.js:443:25)
    at loader (/Users/tema/babel-double-source/node_modules/babel-register/lib/node.js:128:5)
    at Object.require.extensions.(anonymous function) [as .js] (/Users/tema/babel-double-source/node_modules/babel-register/lib/node.js:138:7)
    at Module.load (module.js:355:32)
    at Function.Module._load (module.js:310:12)
    at Module.require (module.js:365:17)
    at require (module.js:384:17)
    at /Users/tema/babel-double-source/node_modules/mocha/lib/mocha.js:216:27
    at Array.forEach (native)
    at Mocha.loadFiles (/Users/tema/babel-double-source/node_modules/mocha/lib/mocha.js:213:14)
    at Mocha.run (/Users/tema/babel-double-source/node_modules/mocha/lib/mocha.js:453:10)
    at Object.<anonymous> (/Users/tema/babel-double-source/node_modules/mocha/bin/_mocha:393:18)
    at Module._compile (module.js:460:26)
    at Object.Module._extensions..js (module.js:478:10)
    at Module.load (module.js:355:32)
    at Function.Module._load (module.js:310:12)
    at Function.Module.runMain (module.js:501:10)
    at startup (node.js:129:16)
    at node.js:814:3
npm ERR! Test failed.  See above for more details.
```
