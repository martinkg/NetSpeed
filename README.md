### Extension to show internet usage speed on gnome

* Check prefences to adjust the sizes

* Use middle click to toggle showing sum.

### Installation

```bash
git clone https://github.com/martinkg/NetSpeed.git
meson Netspeed /tmp/g-s-NetSpeed-build
ninja -C /tmp/g-s-NetSpeed-build install
gnome-extensions enable netspeed@hedayaty.gmail.com
```

Under X11, you may need to restart GNOME Shell (<kbd>Alt</kbd>+<kbd>F2</kbd>, <kbd>r</kbd>, <kbd>⏎</kbd>)
after that. Under Wayland you need to logout and login again.

