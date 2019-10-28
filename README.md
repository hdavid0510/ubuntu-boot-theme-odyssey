# Smasung Odyssey Ubuntu Boot Theme

## Environment
This theme is tested with Ubuntu 16.04 and Ubuntu 18.04 with `NT800G5M` model.
Every resources are designed to be used in 1920x1080 display.

## How to Install
### GRUB boot menu theme
file : `grub-themes-odyssey.tar.gz`
1. Unzip file
2. Extracted `themes/odyssey` directory should be at `/boot/grub/themes/odyssey`.
3. Update GRUB with
```
update-grub
```
4. Check if GRUB theme successfully installed.

### plymouth theme
file : `plymouth-themes-odyssey.tar.gz`
1. Unzip file
2. Extracted `odyssey` directory should be at `/usr/share/plymouth/themes/odyssey`.
3. Update alternative with:
```
update-alternative --install default.plymouth /usr/share/plymouth/themes/odyssey/odyssey.plymouth
```
4. Check if plymouth theme successfully installed.