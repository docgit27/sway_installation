
## Wayland compositor

Assuming you have already installed a minimal Debian 12 install.
The series of shell scripts are intended to facilitate installing popular window managers.

Within the install.sh file, you can choose to install the following window managers:

* sway

**You can select between vanilla(non-customized) and completely customized (my personal customization)** 

# Steps to follow for the installation

``` 
wget https://github.com/docgit27/sway_installation/install.sh

cd ~/sway_installation 

chmod +x install.sh

./install.sh

rm install.sh

```

There's a good "compositor" possibility for the purpose of having a window manager for Wayland too.
Added scripts:

* nwg-look - installs an lxappearance program to use GTK themes and icons in Wayland.
* rofi-wayland - designed to behave like rofi(xorg) but in Wayland.

NOTE:  The recommended login manager will be gdm3 or sddm.
"# sway_installation" 