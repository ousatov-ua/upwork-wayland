Upwork-wayland
==============
This script add possibility to make screenshots by Upwork timer.

All you need is run it during login (as autostart)

This project is a simple bridge between Upwork or any other tool supporting Gnome's screenshot protocol
and your favourite [wlroots](https://github.com/swaywm/wlroots-rs)-based Wayland composer like [Sway](https://swaywm.org).

Make sure that both the script and Upwork application use the same DBus session bus,
i.e. their DBUS_SESSION_BUS_ADDRESS environment variables have the same value!
Otherwise they won't be able to see each other.


As usual, it will just work by default without additional actions.

Dependencies
------------

- Python 3.5 or newer
- `dbus-next` python package (`pip install dbus-next` should work)
- [`flameshot` tool](https://flameshot.org/) somewhere in `PATH`

<!-- - Optional: [`swayidle`](https://github.com/swaywm/swayidle) in `PATH` - for accurate idle time calculation -->
