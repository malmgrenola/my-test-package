# my-test-package

My very first package with npm and a hello world example.

Echo a string with a message in uppercase and original format for example `You anonymously said: FISH from the original "Fish"`

## Install

`npm i @malmgrenola/my-test-package` or `yarn add @malmgrenola/my-test-package`

## Usage

```javascript
const myEcho = require("@malmgrenola/my-test-package");
console.log(myEcho("Fish"));
```

returns the output `You anonymously said: FISH from the original "Fish"`
