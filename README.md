# Parch linux grub theme

## Install

```sh
git clone https://github.com/parchlinux/parch-grub-theme && cd parch-grub-theme
sudo cp parch-grub-* /usr/share/grub/themes # or light!
```

Uncomment and edit following line in /etc/default/grub to selected theme:

* light

```sh
GRUB_THEME="/usr/share/grub/themes/parch-grub-light"
```

* dark

```sh
GRUB_THEME="/usr/share/grub/themes/parch-grub-dark"
```

then Update grub:

```sh
sudo grub-mkconfig -o /boot/grub/grub.cfg
```
