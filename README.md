My build of DWM


# Modifications
## Added Patches :
- Autostart
- Fullscreen

# Installation

After compiling add a file like this as /usr/share/xsessions/dwm.desktop

```
[Desktop Entry]
Name=dwm
Comment=The comment you want to appear when hovered
Exec= dwm
Type=Application
```

To make autostart script work run this command
```
ln -s autostart.sh $XDG_DATA_HOME/dwm/autostart.sh
```
