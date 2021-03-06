# Live Sass Compiler
[![VSCode Marketplace Badge](https://img.shields.io/vscode-marketplace/v/glenn2223.live-sass.svg?label=VSCode%20Marketplace&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=glenn2223.live-sass) [![Total Install](https://img.shields.io/vscode-marketplace/d/glenn2223.live-sass.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=glenn2223.live-sass) [![Average Rating Badge](https://img.shields.io/vscode-marketplace/r/glenn2223.live-sass.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=glenn2223.live-sass) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://github.com/glenn2223/vscode-live-sass-compiler/)

**_Like it? [Please leave a review](https://marketplace.visualstudio.com/items?itemName=glenn2223.live-sass#review-details). Found something wrong? [Report an issue](https://github.com/glenn2223/vscode-live-sass-compiler/issues/new)._**

A VSCode Extension that help you to compile/transpile your SASS/SCSS files to CSS files at real-time with live browser reload.

![App Preview](./images/Screenshot/AnimatedPreview.gif)

## Usage/Shortcuts
1. Click to `Watch Sass` from the status bar to turn on the live compilation and then click to `Stop Watching Sass` from the status bar to turn off live compilation . 
![Status bar control](./images/Screenshot/statusbar.jpg)

2. Press `F1` or `ctrl+shift+P` and type `Live Sass: Watch Sass` to start live compilation or, type `Live Sass: Stop Watching Sass` to stop a live compilation.
3. Press `F1` or `ctrl+shift+P` and type `Live Sass: Compile Sass - Without Watch Mode ` to compile SASS or SCSS for one time.

## Features
* Live SASS & SCSS compile.
* Customizable file location of exported CSS.
* Customizable exported CSS style (`expanded`, `compressed`).
* Customizable extension name (`.css` or `.min.css`).
* Quick status bar control.
* Exclude specific folders by settings. 
* Live reload to browser (Dependency on `Live Server` extension).
* Autoprefix support (See settings section)

## Installation
Open VSCode Editor and Press `ctrl+P`, type `ext install glenn2223.live-sass`.

## Settings
All settings are now listed in the [Settings Docs](./docs/settings.md).

## FAQ
*All FAQs are now listed in the [FAQ Docs](./docs/faqs.md)*

## Extension Dependency 
This extension has dependency on _[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)_ extension for live browser reload.

## What's new ?

**Breaking changes in v4:**
- Output options are now only `expanded` and `compressed`
- Only works on VS Code v1.50 and newer

### 4.4.1 - 2021-01-31

### Fixed
- Fixed: `forceBaseDirectory` has full support in multi-root workspaces
- Fixed: the path in `forceBaseDirectory` is now checked to see if it exists. If not a user friendly message is displayed in the output
- Fixed: an error when checking files would still compile what it could. This would hide the error message from the user
- Incorrect patern matches in settings show user friendly messages rather than "does not match pattern"

*See the full changelog [here](CHANGELOG.md).*

## LICENSE
This extension is licensed under the [MIT License](LICENSE)

## Thank you Ritwick Dey
A big thank you to [@ritwickdey](https://github.com/ritwickdey) for all his work. However, as they are no longer maintaining the [original work](https://github.com/ritwickdey/vscode-live-sass-compiler), I have released my own which has built upon it.
