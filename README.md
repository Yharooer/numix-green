Numix Green
==================

Numix Green is a modern flat theme with a combination of light and dark elements. It supports Gnome, Unity, XFCE and Openbox.

Numix Green is a fork of [Numix](https://github.com/shimmerproject/Numix). Numix is a part of the [Numix Project](http://numixproject.org).

### Manual installation

Extract the zip file to the themes directory i.e. `/usr/share/themes/`

To set the theme in Gnome, run the following commands in Terminal,

```
gsettings set org.gnome.desktop.interface gtk-theme "Numix"
gsettings set org.gnome.desktop.wm.preferences theme "Numix"
```

To set the theme in Xfce, run the following commands in Terminal,

```
xfconf-query -c xsettings -p /Net/ThemeName -s "Numix"
xfconf-query -c xfwm4 -p /general/theme -s "Numix"
```

### Requirements

GTK+ 3.6 or above

Murrine theme engine

### License

Numix Green is a fork of [Numix](https://github.com/shimmerproject/Numix) and is lisensed under [GPL-3.0+](https://github.com/shimmerproject/Numix/blob/master/LICENSE).
