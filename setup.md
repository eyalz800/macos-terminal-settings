Install karabiner-elements:
1. https://karabiner-elements.pqrs.org/
2. Import configuration:
```sh
cp karabiner.json ~/.config/karabiner/
```
Add `/Library/Application Support/org.pqrs/Karabiner-Elements/bin/karabiner_grabber/observer` to privacy settings.

Install brew:
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/ezedaka/.profile
eval "$(/opt/homebrew/bin/brew shellenv)"
```

Install kitty:
```sh
brew install kitty
cp kitty.conf ~/.config/kitty/
```
Install the `MesloLGM Nerd Font Mono.ttf`

Function keys, control key, and keyboard stuff:
System Preferences -> Keyboard -> Use F1, F2, ... as standard function keys
System Preferences -> Keyboard -> Modifier Keys: Globe to Control, Control to fn
System Preferences -> Keyboard: Set Globe to nothing
