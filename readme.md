<p align="center">
  <img src="https://i.imgur.com/nBvf1Ju.png" height="150">
  <p align="center">☢️ Console Logger with Emoji Support<p>
  <p align="center">
  <a href="https://travis-ci.org/xxczaki/mija"><img src="https://travis-ci.org/xxczaki/mija.svg?branch=master" alt="Build Status"></a>
  <a href="https://github.com/sindresorhus/xo"><img src="https://img.shields.io/badge/code_style-XO-5ed9c7.svg" alt="Code Style"></a>  
</p>
</p>

## Install

```bash
npm install mija
```

<a href="https://www.patreon.com/akepinski">
	<img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" width="160">
</a>

## Usage

<img src="https://imgur.com/KBP1qu0.png" alt="Screenshot" align="right" width="279"></a>

```js
const mija = require('mija');

mija.success('Success!');
```
## API

```js
mija.option(text);
```
or
```js
mija.custom(emoji, text);
```

**option**

Any available [option](https://github.com/xxczaki/mija#options).

**text**

Type: `string`

Custom message.

**emoji**

Type: `string`

Custom emoji. Can only be used with `mija.custom`.

## Options

`info`

`warn`

`error`

`success`

`magic`

`inprogress`

`stop`

`repeat`

`experimental`

`danger`

`custom`

## Related

* [xa](https://github.com/xxczaki/xa) - Simple console logger, that works in Node.js, Electron and the Browser

### License

MIT
