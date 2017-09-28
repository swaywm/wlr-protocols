# sway-protocols

Wayland protocols being developed to make Sway's desktop shell generic, to
allow sway components to be reused in third party compositors and third party
shell components to be used in sway.

Note that these protocols are generally privledged and will require
authentication with orbital's authorizor protocol before use.

WIP

Please make Github issues to discuss these protocols and propose use-cases that
these won't fulfull. The goal is to stop making users compromise when they
switch to Wayland.

## surface-layers

This protocol describes several layers clients can use for rendering at a
specific z depth. This protocol should support use-cases like:

- wallpapers
- desktop icons
- panels
- screen lockers
- on screen keyboards
- notifications
- dmenu/rofi
- slop

[Protocol](https://github.com/SirCmpwn/sway-protocols/blob/master/unstable/surface-layers.xml)

[Discussion](https://github.com/SirCmpwn/sway-protocols/issues/1)
