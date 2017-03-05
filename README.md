# Cpitt's Dotfile

Dotfiles managed using a bare git repository



## Installation:
```
curl -Lks https://raw.githubusercontent.com/cpitt/dotfiles/master/.dotfile-manager.sh | /bin/bash
```

## Pulling dotfiles from repo
```
config pull
```

## Adding/updating new/changed dotfiles
```
config add .newFile
config commit -m 'adding .newFile'
config push
```
