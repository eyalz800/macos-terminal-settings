## Install karabiner-elements:
1. https://karabiner-elements.pqrs.org/
2. Import configuration:
```sh
cp karabiner.json ~/.config/karabiner/
```
Add `/Library/Application Support/org.pqrs/Karabiner-Elements/bin/karabiner_grabber/observer` to privacy settings.

## Install Brew:
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/ezedaka/.profile
eval "$(/opt/homebrew/bin/brew shellenv)"
```

## Install kitty:
```sh
brew install kitty
cp kitty.conf ~/.config/kitty/
```
Install the `MesloLGM Nerd Font Mono.ttf`

## Function keys, control key, and keyboard stuff:
System Preferences -> Keyboard: Use F1, F2, ... as standard function keys
System Preferences -> Keyboard: Set Globe to nothing
System Preferences -> Keyboard: Key repeat to max, Delay Until Repeat to 3 (zero based)
System Preferences -> Keyboard -> Modifier Keys: Globe to Control, Control to fn
System Preferences -> Keyboard -> Shortcuts: Disable display shortcut F14, F15, and
System Preferences -> Keyboard -> Shortcuts: Disable mission control Application Windows, and Show Desktop
System Preferences -> Keyboard -> Shortcuts: Change mission control to ctrl+command+up
System Preferences -> Keyboard -> Shortcuts: Change mission control move to left and move to right to ctrl+command+left/right
System Preferences -> Trackpad -> Uncheck "Swipe between pages" and "App Expose"

## Install Prefs Editor
https://apps.tempel.org/PrefsEditor/

## Install Rectangle
https://rectangleapp.com/
```sh
cp com.knollsoft.Rectangle.plist ~/Library/Preferences/com.knollsoft.Recta
ngle.plist
```
1. Hide menu bar icon.
2. Clear all shortcuts and add "Left/Right Half" to Command+Options left right "Maximize" "Almost maximize" to up down.

## Install iterm2
https://iterm2.com/
```sh
cp com.googlecode.iterm2.plist ~/Library/Preferences/com.googlecode.iterm2.plist
```
