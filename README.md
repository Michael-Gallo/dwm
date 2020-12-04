My build of DWM


# Modifications
## Added Patches :
- Autostart
- Bar Height
- Fullscreen
- Useless Gaps
- fixborders (found in alpha patch section)
- maximize
- circlelayouts
- statusallmons
- focusonclick

## Personalization:
- Added icons for tags (needs ttf-font-awesome installed)
- Set number of tags to 5
- Added gaps and colorful window borders
- Green and Black Color Scheme
- Set master window factor to 50% (Master will take up 1/2 of the screen)
- Modkey changed to super
- Launcher keybinds removed (I use sxhkd for those)
- Set barheight to 22
- Status bar displays the same on all monitors
- removed sloppy focus, edited focusonclick patch so it wouldn't ruin floating behavior
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
ln -s $HOME/dwm/autostart.sh $XDG_DATA_HOME/dwm/autostart.sh 
```
