# capteer

[![NPM Version](https://img.shields.io/npm/v/capteer.svg?style=flat)](https://www.npmjs.com/package/capteer) 
[![NPM Downloads](https://img.shields.io/npm/dm/capteer.svg?style=flat)](https://www.npmjs.com/package/capteer) 
[![License](https://img.shields.io/npm/l/capteer.svg?style=flat)](https://www.npmjs.com/package/capteer) 

> Capture web page with puppeteer.

### Install

```sh
npm install capteer -g
```


### Usage

#### Command

```sh
capteer <url> [filename] [options]
```

#### Arguments

```sh
url         url of the web page to capture
filename    name of the image file to save
```

#### Options

```sh
-H, --height <height>  set viewport height
-W, --width <width>    set viewport width
-D, --delay <delay>    milliseconds before capture
-V, --viewport         only capture the viewport
```

### Example

```sh
capteer https://github.com/myst729/capteer
```
