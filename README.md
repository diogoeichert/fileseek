[![code style](https://img.shields.io/badge/code_style-classic-blue.svg)](http://diogoeichert.github.io/eslint-config-classic)
[![downloads](https://img.shields.io/npm/dt/fileseek.svg)](https://www.npmjs.com/package/fileseek)
[![license](https://img.shields.io/github/license/diogoeichert/fileseek.svg)](LICENSE)
[![npm version](https://img.shields.io/npm/v/fileseek.svg)](https://www.npmjs.com/package/fileseek)

# fileseek
Search files recursively

## usage
```
npm install fileseek --save
```
Then:
```
const fileseek = require("fileseek");
fileseek("/path/to/dir", /expression/, recursive);
```

Set `recursive` to `false` to disable recursion (defaults to `true`)
