# dwm
my personalized build of dwm

# setup
before starting, install the dependencies

### mandatory
* libX11
* libXft
* make
* gcc

note - you may need the dev variants of the libX11/Xft packages depending on your distro.

note - even though gcc is listed as mandatory, you can edit config.mk to support any compiler you want.

### optional
* shell scripts for dwmblocks, to install, run:

```sh
$ cd scripts
$ chmod +x *
# mv * /usr/local/bin` (doesn't have to be /usr/local/bin, just has to be on $PATH)
```

* rxvt-unicode
* maim
* xclip
* xrandr
* git
* vim

### install
to install dwm and/or dwmblocks, run:

```sh
$ cd {dwm or dwmblocks}
# make clean install
```sh
