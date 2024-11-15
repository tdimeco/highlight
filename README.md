<p align="center">
	<img src="https://user-images.githubusercontent.com/212034/28132290-577374c6-6777-11e7-9dd2-802606985c2b.png" width="256" height="256">
</p>

[[English](https://github.com/taggon/highlight/blob/master/README.md)]
[[한국어](https://github.com/taggon/highlight/blob/master/docs/README.ko.md)]

# Highlight

Highlight is a rich-featured syntax highlighter for Keynote slides that allows you to get syntax-highlighted code in RTF with one click.
Its main feature is based on [highlight.js](https://highlightjs.org/), which means a lot of languages and styles are available.
Check out the [demo](https://highlightjs.org/static/demo/) to see what you get with the application.

This repository is a fork of [taggon/highlight](https://github.com/taggon/highlight), which is the original app.
I made some changes to modernize the app, update highlight.js and distribute it as a Homebrew Cask.

## Features

From highlight.js:

* 192 languages and 238 styles
* Automatic language detection
* Multi-language code highlighting

Original features:

* Line numbers
* Custom font
* Global hotkey - you don't even need to click.
* Automatic updates
* Supports multi-language UI
  * English
  * Korean
  * Turkish - Thanks to [@tosbaha](https://github.com/tosbaha)
  * Chinese Simplified - Thanks to [@xnth97](https://github.com/xnth97)

Want to add support for your language? Send me translations! :)

## Installation

### Homebrew

You can install the app using [Homebrew](https://brew.sh/):

```bash
brew install --cask tdimeco/apps/highlight
```

This is the recommended way to install the app.
The app auto updates with Homebrew.

The Homebrew tap is maintained by [@tdimeco](https://github.com/tdimeco).

### Manual

You can download the app from the [Releases](https://github.com/tdimeco/highlight/releases) page.
The app does not auto update in this case.

## Usage

![](https://user-images.githubusercontent.com/212034/28166880-98238d06-6814-11e7-9418-83a286a8a67d.gif)

* When you execute the application, you will see a highlighter icon on the menubar as shown in the screenshot.
![](https://user-images.githubusercontent.com/212034/28166990-f05c99fe-6814-11e7-9ec8-c7569a20763d.png)
* Copy any code you want to colorize.
* Click on the icon to open the popup menu. Select Highlight Code and then pick your programming language
or just choose the auto-detect one. Now the code is syntax-highligted.
* Paste the code wherever you want (e.g. Keynote).

Do you like to customize the results? Just open the Preferences dialog. You will see how.

## How to build

You need to setup [NodeJS](https://nodejs.org), then run:

```
$ npm install
```

Open the project by double-clicking `Highlight.xcodeproj` then build it. It should just work.

## Contribution

Highlight supports multi-language UI, currently only for few languages including English and Korean.
If you're interested in translating the application, start by copying
[the Korean translation folder](https://github.com/taggon/highlight/tree/master/Highlight/ko.lproj) into your respective language folder
(e.g. pr.lproj for Portuguese, ru.lproj for Russian, etc).

You need to translate all files in the folder.
