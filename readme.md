This is a sample NPM module created in Learn Enough JavaScript to Be Dangerous by uninem.

The module can be used as follows:

$ npm install --global uninem-palindrome
$ vim test.js
let Phrase = require("uninem-palindrome");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$ node test.js
true
