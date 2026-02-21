# arch-linux-setup

# enable-boot-text
to look cooler
```
sudo vim /etc/default/grub
```
remove quiet if it exists from **GRUB_CMDLINE_LINUX_DEFAULT**

# swapcaps-with-localectl

**set-x11-keymap LAYOUT [MODEL [VARIANT [OPTIONS]]]**

```
sudo localectl set-x11-keymap us "" "" ctrl:swapcaps
```

us is the keyboard layout, "" and "" is a place holder for model and variant to use sys defaults, and ctrl:nocaps is the optswapcaps

- [localectl](https://wiki.archlinux.org/title/Xorg/Keyboard_configuration#Using_localectl)
