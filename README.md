# My DWM Configuration Files
## Patches
* [fullgaps](https://dwm.suckless.org/patches/fullgaps/)
* [barpadding](https://dwm.suckless.org/patches/barpadding/)
* [statuspadding](https://dwm.suckless.org/patches/statuspadding/)
* Very minimal custom patch allowing for more precise resizing.

    ```
	{ MODKEY|ShiftMask,             XK_h,      setmfact,       {.f = -0.01} },
	{ MODKEY|ShiftMask,             XK_l,      setmfact,       {.f = +0.01} },
    ```
* Also removed window titles, version info, and layout status.

