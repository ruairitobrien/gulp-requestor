(PLUGIN AUTHOR: Please read [Plugin README conventions](https://github.com/wearefractal/gulp/wiki/Plugin-README-Conventions), then delete this line)

# gulp-gulp-requestor
[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url]  [![Coverage Status][coveralls-image]][coveralls-url] [![Dependency Status][depstat-image]][depstat-url]

> gulp-requestor plugin for [gulp](https://github.com/wearefractal/gulp)

## Usage

First, install `gulp-gulp-requestor` as a development dependency:

```shell
npm install --save-dev gulp-gulp-requestor
```

Then, add it to your `gulpfile.js`:

```javascript
var gulp-requestor = require("gulp-gulp-requestor");

gulp.src("./src/*.ext")
	.pipe(gulp-requestor({
		msg: "Hello Gulp!"
	}))
	.pipe(gulp.dest("./dist"));
```

## API

### gulp-requestor(options)

#### options.msg
Type: `String`  
Default: `Hello World`

The message you wish to attach to file.


## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)

[npm-url]: https://npmjs.org/package/gulp-gulp-requestor
[npm-image]: https://badge.fury.io/js/gulp-gulp-requestor.png

[travis-url]: http://travis-ci.org/ruairitobrien/gulp-gulp-requestor
[travis-image]: https://secure.travis-ci.org/ruairitobrien/gulp-gulp-requestor.png?branch=master

[coveralls-url]: https://coveralls.io/r/ruairitobrien/gulp-gulp-requestor
[coveralls-image]: https://coveralls.io/repos/ruairitobrien/gulp-gulp-requestor/badge.png

[depstat-url]: https://david-dm.org/ruairitobrien/gulp-gulp-requestor
[depstat-image]: https://david-dm.org/ruairitobrien/gulp-gulp-requestor.png
