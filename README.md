# Reader.js
[![Build Status](https://travis-ci.org/ridi/Reader.js.svg?branch=master)](https://travis-ci.org/ridi/Reader.js)

Javascript library for RIDI EPUB Viewer written in ECMAScript 6

## Install
```
$ npm install @ridi/reader.js
```

## Structure
```
└─┬ root
  ├── LICENSE
  ├── package.json
  ├── README.md
  ├─┬ android
  | └─ index.js
  ├─┬ ios
  | └─ index.js
  └─┬ web
    └─ index.js
```

## Compatbility
- iOS 8-11
- Android 4-8 (API Level 14-26)
- Chrome 30~64
- Safari 9~11
- IE 11

## Usage

```js
import { Reader, Context, Util } from '@ridi/reader.js/[android|ios|web]';
```
 

## Development

### Install
You can install it with the following command:
```
$ git clone git@github.com:ridi/Reader.js.git
$ make setup
```

### Build
You can build it with the following command in Reader.js folder:
```
$ npm run [build|watch]
```
> [grunt-cli](https://github.com/gruntjs/grunt-cli) is required to build Reader.js
