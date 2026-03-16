## openbox-window-snap

Patch to enable window snapping by dragging the window (aero snap) for openbox.

![](https://github.com/koyakonsta/openbox-window-snap-quad/blob/master/demo.gif)

Usage:

```bash
git clone https://github.com/danakj/openbox
cp openbox-window-snap.diff openbox
cd openbox
git apply openbox-window-snap.diff
```

Then build openbox according to the instructions [here.](http://openbox.org/wiki/Help:Installing)

This probably won't work with multiple monitors or desktops.
