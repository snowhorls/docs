# arch-linux-setup

# enable-boot-text
to look cooler
```
sudo vim /etc/default/grub
```
remove quiet if it exists from **GRUB_CMDLINE_LINUX_DEFAULT**

# swapescape-with-localectl

see **set-x11-keymap LAYOUT [MODEL [VARIANT [OPTIONS]]]** in man page

```
sudo localectl set-x11-keymap us "" "" caps:swapescape
```
then reboot

- **us** is the keyboard layout, <br>
- **""** and **""** are a place holder for model and variant and tells it to use sys defaults instead, <br>
- caps:swapescape is the option

- [localectl](https://wiki.archlinux.org/title/Xorg/Keyboard_configuration#Using_localectl)
