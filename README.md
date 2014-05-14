# post-merge-make

Runs `make post-merge` command after git pull or merge.

[![NPM][post-merge-make-icon]][post-merge-make-url]

[![Build status][post-merge-make-ci-image]][post-merge-make-ci-url]
[![dependencies][post-merge-make-dependencies-image]][post-merge-make-dependencies-url]
[![devdependencies][post-merge-make-devdependencies-image]][post-merge-make-devdependencies-url]
[![endorse][endorse-image]][endorse-url]

### Installation

From the root of your repo:

```
npm install post-merge-make
```

If you have Node package.json, save this module as a dev dependency using `--save-dev`

### Configuration

Specify target in your Makefile

```
post-merge: install build

install: ...
```

### Related

Run different commands from Node project on commit or push using
[pre-git](https://github.com/bahmutov/pre-git)

### Small print

Author: Gleb Bahmutov &copy; 2014

* [@bahmutov](https://twitter.com/bahmutov)
* [glebbahmutov.com](http://glebbahmutov.com)
* [blog](http://bahmutov.calepin.co/)

License: MIT - do anything with the code, but don't blame me if it does not work.

Spread the word: tweet, star on github, etc.

Support: if you find any problems with this module, email / tweet /
[open issue](https://github.com/bahmutov/post-merge-make/issues?state=open) on Github

### License

MIT

[post-merge-make-icon]: https://nodei.co/npm/post-merge-make.png?downloads=true
[post-merge-make-url]: https://npmjs.org/package/post-merge-make
[post-merge-make-ci-image]: https://travis-ci.org/bahmutov/post-merge-make.png?branch=master
[post-merge-make-ci-url]: https://travis-ci.org/bahmutov/post-merge-make
[post-merge-make-dependencies-image]: https://david-dm.org/bahmutov/post-merge-make.png
[post-merge-make-dependencies-url]: https://david-dm.org/bahmutov/post-merge-make
[post-merge-make-devdependencies-image]: https://david-dm.org/bahmutov/post-merge-make/dev-status.png
[post-merge-make-devdependencies-url]: https://david-dm.org/bahmutov/post-merge-make#info=devDependencies
[endorse-image]: https://api.coderwall.com/bahmutov/endorsecount.png
[endorse-url]: https://coderwall.com/bahmutov
