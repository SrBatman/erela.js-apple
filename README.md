<div align = "center">
<a href="https://www.npmjs.com/package/erela.js-apple">
<img src="https://img.shields.io/npm/dw/erela.js-apple?color=CC3534&logo=npm&style=for-the-badge" alt="Downloads">
</a>

<a href="https://www.npmjs.com/package/erela.js-apple">
<img src="https://img.shields.io/npm/v/erela.js-apple?color=red&label=Version&logo=npm&style=for-the-badge" alt="Npm version">
</a>
<br>


<hr>
</div>
Apple Music plugin for Erela.JS


## What is this ?
This a plugin for Erela.JS to allow the use of AppleMusic URL's, it uses direct URL's being tracks, albums, and playlists and gets the YouTube equivalent.  


- https://music.apple.com/mx/album/happier-than-ever/1564530719

- https://music.apple.com/es/album/anymore/1444563557?i=1444563560

- https://music.apple.com/us/playlist/todays-hits/pl.f4d106fed2bd41149aaacabb233eb5eb
## Installation

**NPM** :

`npm install erela.js-apple`
## Example Usage

```javascript
const { Manager } = require("erela.js");
const AppleMusic  = require("erela.js-apple");

const manager = new Manager({
  plugins: [
    // Initiate the plugin 
    new AppleMusic()
  ]
});

manager.search("https://music.apple.com/mx/album/happier-than-ever/1564530719");
```
