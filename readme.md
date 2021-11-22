This is a sample NPM module.
The module can be used as follows:

$ npm install --global upgradeseason-palindrome
$ vim test.js
let Phrase = require("upgradeseason-palindrome");
let hotPhrase = new Phrase("Too hot or to hoot");
console.log(hotPhrase.palindrome());
$ node test.js
true
