# Zed (Editor)
Download [Brew](https://github.com/BosEriko/brew) as your package manager then install [Zed](https://formulae.brew.sh/cask/zed).

## Install Zed
```sh
brew install --cask zed
```

## Install the config
Make sure to remove or move your current `Zed` directory
```sh
git clone https://github.com/BosEriko/zed.git ~/.config/zed
```

## Install the Extensions
1. [Aura Theme](https://zed.dev/extensions/aura-theme)
2. [Charmed Icons](https://zed.dev/extensions/charmed-icons)

## Enable Repeated Keys (macOS)
Enable repeated keys to avoid pop up on key hold with the following:
```sh
defaults write -g ApplePressAndHoldEnabled -bool false
```
*Note: Restart to make it take effect*
