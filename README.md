HiResStartupItem
================

Make use of the Retina display in your MacBookPro irrespective of official support by setting the screen resolution to 2048x1280 at login.

### Dependencies ###
- [Homebrew](http://brew.sh) // `ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"`
- [screenresolution](https://github.com/jhford/screenresolution) // `brew install screenresolution`


### Installation ###
```
osascript -e 'tell application "System Events" to make new login item with properties { path: "/PATH_TO_APP/HiResStartupItem.app" } at end'
```
