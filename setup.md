* Install karabiner-elements:
1. https://karabiner-elements.pqrs.org/
2. Import configuration:
```sh
cp karabiner.json ~/.config/karabiner/
```
Add `/Library/Application Support/org.pqrs/Karabiner-Elements/bin/karabiner_grabber/observer` to privacy settings.

* Install brew:

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

```sh
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/ezedaka/.profile
eval "$(/opt/homebrew/bin/brew shellenv)"
```

* Install kitty:
```sh
brew install kitty
```

