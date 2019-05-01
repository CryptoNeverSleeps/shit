
Debian
====================
This directory contains files used to package shitd/shit-qt
for Debian-based Linux systems. If you compile shitd/shit-qt yourself, there are some useful files here.

## shit: URI support ##


shit-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install shit-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your shitqt binary to `/usr/bin`
and the `../../share/pixmaps/shit128.png` to `/usr/share/pixmaps`

shit-qt.protocol (KDE)

