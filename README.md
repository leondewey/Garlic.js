#Garlic.js

[![Build Status](https://secure.travis-ci.org/guillaumepotier/Garlic.js.png?branch=master)](https://travis-ci.org/guillaumepotier/Garlic.js)

Garlic.js allows you to automatically persist your forms' text and select field values locally, until the form is submitted. This way, your users don't lose any precious data if they accidentally close their tab or browser.

#Demonstration / Documentation

http://garlicjs.org/

#Version

1.0.0

See CHANGELOG for more info.

#TODO

* Improve doc and api;
* Refactorize some code;
* Work on an alternative to Local Storage for non compatible browsers;
* Work on cases where server put content in text fields, let the user choose bw server or Local Storage version;
* Improve tests coverage;
* Improve compatibility;
* And much more, for fun!

#Run tests

* In your browser: go to `tests/index.html`
* Headless tests: install mocha-phantomjs with npm: `npm install -g mocha-phantomjs` and then run `./bin/test-suite.sh`

#Make production minified versions

You'll need ruby, and Google Closure compiler: `gem install closure-compiler`. Then, just call:

`./bin/build.sh version` where version is the build release. eg: `./bin/build.sh 1.0.0`

They'll be created and dumped in the dist/ directory

#Contributors

* @cdmoyer
* @johnrees
* @Marfa
* @leondewey

#Licence

MIT - See LICENCE.md
