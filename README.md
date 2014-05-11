# st - simple terminal

This is a clone of [suckless.org](http://suckless.org) the coolest terminal client **st**.
Light, stable, simple and fast. **tmux** brings in all other needed features.

A [PKGBUILD](https://aur.archlinux.org/packages/st-pizz/) was added for easy installation on Arch.

## Customizations

- **Droid Sans** font usage.
- **solarized** dark - color scheme.
- **xcompmgr** is optional, when turned on - opacity configuration is taken into account for transparency.

## Screen

![Screenshot](https://raw.github.com/pizzooid/st/master/screen.png)

## Requirements

In order to build st you need:

- the [PKGBUILD](https://aur.archlinux.org/packages/st-pizz/)

## Installation

makepkg or your favorite aur manager

## Running st

If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -s st.info

Run it with tmux:

    st -e tmux

See the man page for additional details.

## Credits

Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.
It was forked from [l3pp4rd/st](https://github.com/l3pp4rd/st).
