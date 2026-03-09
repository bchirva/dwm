# dwm
Patched build of [dwm](dwm.suckless.org)

## Applied patches:
* [xrdb](https://dwm.suckless.org/patches/xrdb/)
* [restartsig](https://dwm.suckless.org/patches/restartsig)
* [fullgaps](https://dwm.suckless.org/patches/fullgaps)
* [statuspadding](https://dwm.suckless.org/patches/statuspadding)
* [actualfullscreen](https://dwm.suckless.org/patches/actualfullscreen)
* [status2d](https://dwm.suckless.org/patches/status2d) with [statuscmd](https://dwm.suckless.org/patches/statuscmd)
* [winicon](https://dwm.suckless.org/patches/winicon)
* [barpadding](https://dwm.suckless.org/patches/barpadding)

## Additional dependencies
* imlib2

## Custom changes:

1. **Tag indication**
Tag indication by names with "occupation square" has been replaced with NerdFont icons.
The list of tags is displayed up to the last active one (e.g., if the last active tag out of 9 is 7, then only 7 icons will be shown).

Commit `3b274de602bd`

2. **Keybindins**
**st** and **dmenu** spawning has been removed in favor of 3rd party launchers (e.g., [sxhkd](https://github.com/baskerville/sxhkd))
