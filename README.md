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
url         url of the web page to capture (required)
filename    name of the image file to save (optional)
```

#### Options

```sh
-H, --height <height>  height of the browser viewport in pixel
-W, --width <width>    width of the browser viewport in pixel
-D, --delay <delay>    milliseconds to wait before taking screenshot
-R, --region           only capture the viewport, omit to capture full page
```

### Example

```sh
capteer https://github.com/myst729/capteer
```
