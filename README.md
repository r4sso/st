# st - simple terminal

[st](https://st.suckless.org/) is a simple terminal emulator for X which sucks less.

## Patch
Patch used in this fork:
- scrollback


## Requirements

In order to build st you need the Xlib header files.

- [Iosevka](https://github.com/be5invis/Iosevka)

(Alpine Linux 3.19):  
Install Fonts:
```
apk add font-iosevka
```

Install build dependencies:
```
apk add make gcc musl-dev ncurses fontconfig-dev freetype-dev libx11-dev libext-dev
```

### Installation

Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

```
$ git clone https://github.com/r4sso/st
$ cd st
# make clean install
```

