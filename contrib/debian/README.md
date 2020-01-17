
Debian
====================
This directory contains files used to package novacashd/novacash-qt
for Debian-based Linux systems. If you compile novacashd/novacash-qt yourself, there are some useful files here.

## novacash: URI support ##


novacash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install novacash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your novacash-qt binary to `/usr/bin`
and the `../../share/pixmaps/novacash128.png` to `/usr/share/pixmaps`

novacash-qt.protocol (KDE)

