[![Build Status](https://travis-ci.org/devkitPro/wut-tools.svg?branch=master)](https://travis-ci.org/devkitPro/wut-tools)
# wut-tools
Tools for [wut](https://github.com/devkitPro/wut).

Licensed under the terms of the GNU General Public License, version 2 or later (GPLv2+).

## Install

It is recommended to install wut by using the [devkitPro package manager](https://devkitpro.org/wiki/devkitPro_pacman)

```
sudo dkp-pacman -Syu wut-tools
```

## Building

### Dependencies
- autoconf
- libtool
- libz-dev
- pkg-config

### Building

For development purposes you may want to build this from source and replace your existing wut-tools installation:

```
dkp-pacman -R wut-tools
./autogen.sh
mkdir build
cd build
../configure --prefix=$DEVKITPRO/tools
make install
```
