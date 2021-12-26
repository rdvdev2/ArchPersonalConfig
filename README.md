# ArchPersonalConfig
Some of my settings on Arch, uploaded mainly for sync across my devices

## How to use
This repository includes settings for different programs, but none of them will change automatically (you must activate the settings for each of them). First, clone the repository to a suitable location:
```bash
git clone https://github.com/rdvdev2/ArchPersonalConfig ~/.synced_config
```
Some of the files expect the repository to be cloned in `~/.synced_config`, so I recommend against changing the above command unless you're willing to fiddle with all the files.
With the repository cloned, now you can activate the configuration for different applications
```bash
ln -sf ~/.synced_config/sway.conf ~/.config/sway/config # Sway window manager
ln -sf ~/.synced_config/vimrc ~/.vimrc # Vim editor
```

## Inspiration
- The color scheme is OneHalf by sonph ([GitHub](https://github.com/sonph/onehalf))
- The wallpaper was taken from Unsplash, but I'm unable to find it again ([Unsplash](https://unsplash.com/))
