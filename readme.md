# HTML5 Boilerplate Ex
This is custom HTML5 boilerplate based on [HTML5 Boilerplate](https://html5boilerplate.com/) and [Yeomen](https://github.com/yeoman).

## Features
- Generate a various size of Favicon & App Icons
- ES6 and Sass
- Open Graph
- Unit Test Automation by Mocha and Chai
- Travis CI
- Auto-prefix of CSS
- Mobile First Sass File Structure
- HTML, CSS, JS & Image minification
- Align proper tags for better markup and SEO  

*IE series are out of support. 

## Command
Commands below are available.
```
- setup your site
Place favicon.png and modify changeme.json before running the scripts.
npm run setup:icon - generate favicons from /favicon.png(512x512).
npm run setup:info - apply info in changeme.json to files such as index.html, manifest.json

- run and build app 
npm start - serve app for development.    
npm test - run test scripts.    
npm run serve:dist - serve contents for production.   
npm run build - build app for production.  
npm run sass - compile Sass for development.  
npm run tasks - list all gulp tasks. 
```

All tasks are defined in package.json and gulpfile.js. 
If you want to use these commands, please prepare a couple of things, following "Quick Start".

## Installation
#### 1. Install modules by NPM  
Run `npm install` in terminal.  
*If NPM is not installed on your pc, download and install it first.  
https://coderwall.com/p/mhd6nw/install-node-js-on-mac-os-x-and-windows

#### 2. Install GraphicsMagick or ImageMagick
Make sure GraphicsMagick or ImageMagick is installed on your system and properly set up in your PATH.  
*If you don't need Favicon & App Icon Generation, you can skip this step.  

Ubuntu:  
`apt-get install imagemagick`  
`apt-get install graphicsmagick`  

Mac OS X (using Homebrew):  
`brew install imagemagick`  
`brew install graphicsmagick`    

Windows & others:  
http://www.imagemagick.org/script/binary-releases.php

## Quick start
1. Put your favicon.png (512x512) and run `npm run setup:icon` to generate various size of icons.
2. set your site profile in `changeme.json` and run `npm run setup:info` and 

## License
License: [MIT License](https://opensource.org/licenses/MIT)  
Contributors: M.Tonomura([@LeapIn_JP](https://twitter.com/LeapIn_JP))  

#### This Template following third-party resources:
* Yeoman, Copyright 2017-2019 Google  
  License: BSD 2-Clause "Simplified" License  
  Source: <https://github.com/yeoman/>

* HTML5 Boilerplate, Copyright 2017-2019 Google  
  License: MIT "Simplified" License  
  Source: <https://html5boilerplate.com/>

* Bones, Copyright 2017 [Themble](https://themble.com/bones/)  
  License: [WTFPL](http://en.wikipedia.org/wiki/WTFPL)  
  Source: <https://themble.com/bones/>  
