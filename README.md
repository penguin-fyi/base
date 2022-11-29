# penguin-base

Source files for `penguin-base` [PKGBUILD](https://github.com/penguin-fyi/pkgbuilds/blob/main/penguin-base/)

## Depends
- base
- curl
- fail2ban
- git
- gnupg
- man-db
- man-pages
- openssh
- pass
- patch
- pwgen
- sudo
- tmux
- ufw
- unzip
- vi
- w3m
- zip
- zsh

## Configs
- etc/sudoers.d/10-wheel

## Patches
- etc/pacman.conf

## Hooks
- usr/share/libaplm/hooks/90-penguin-config-patch.hook

## Scripts
- usr/share/libaplm/scipts/penguin-config-patch

## Services
- sshd
- ufw

