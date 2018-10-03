# Blank
A blank (black) screensaver for MacOS/OS X.
Tested on 10.12.6 and 10.14 but will propably work on any version.

Inspired by https://superuser.com/a/328670 but even smaller in size.

## Installation

### [Homebrew](http://brew.sh/)
* Run:

    ```
    $ brew tap theseal/blank-screensaver
    $ brew cask install blank-screensaver
    ```
* Follow caveats

### Without Homebrew

* Mojave (10.14):
  * Install the `Blank` screen saver
```
open Blank.saver
```

* Before Mojave (< 10.14):

  * Copy "Blank.qtz" to "~/Library/Screen Savers":
```
cp Blank.qtz ~/Library/Screen\ Savers/
```
* Enable the screensaver(named "Blank") in "Desktop & Screen saver" under "Screen Saver":
```
open /System/Library/PreferencePanes/DesktopScreenEffectsPref.prefPane
```
