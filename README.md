# i3wm-config
This is a i3wm config with some other tools

## 1. Start
install dependencies
arch
```
sudo pacman -S feh compton rofi nm-applet ranger fcitx-im fcitx-configtools fcitx-libpinyin
```

then, get config file
```
git clone https://github.com/lakefish/i3wm-config.git ~/.config/i3/
```

or (for chinese network)
```
git clone https://ghproxy.com/https://github.com/lakefish/i3wm-config.git ~/.config/i3/
```

## About dependencies
- feh (set wall paper)
- compton (provide transparency)
- rofi (start application)
- fcitx (input method)
- nm-applet (network manager)
- ranger (file manager)

Actually, i3wm itself don't need all of this, but I write these in config file for better experience.

