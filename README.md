# karabiner
karabiner config

## Setup Karabiner/goku

### `brew install` karabiner cask and goku formula
```sh
brew install cask karabiner-elements
brew install yqrashawn/goku/goku
brew upgrade goku
// Change profile name to "Default"
```

### clone https://github.com/loudoguno/karabiner to ~/config.file/Karabiner

```sh
git clone https://github.com/loudoguno/karabiner ~/config.files/karabiner
```

### ** symlink recently cloned ~/config.files/karabiner/karabiner.edn to default location for goku config ~/.config/karabiner.edn

```sh
ls -s ~/config.files/karabiner/karabiner.edn ~/.config/karabiner.edn
```

