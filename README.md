dwm
===

Dynamic window manager for X.

`man dwm` for instructions.
`super + F1` for Luke's manual.

Fork of [LukeSmithxyz](https://github.com/LukeSmithxyz/dmenu).
Original from [suckless](https://tools.suckless.org/dmenu/).

Installation
------------

This build of dwm does not block color emoji in the status/info bar, so you must install [libxft-bgra](https://aur.archlinux.org/packages/libxft-bgra/) from the AUR, which fixes a libxft color emoji rendering problem, otherwise dwm will crash upon trying to render one.
Hopefully this fix will be in all libxft soon enough.


```
# make install
```
