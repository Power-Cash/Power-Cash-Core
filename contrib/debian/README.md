
Debian
====================
This directory contains files used to package powercashd/powercash-qt
for Debian-based Linux systems. If you compile powercashd/powercash-qt yourself, there are some useful files here.

## powercash: URI support ##


powercash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install powercash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your powercash-qt binary to `/usr/bin`
and the `../../share/pixmaps/powercash128.png` to `/usr/share/pixmaps`

powercash-qt.protocol (KDE)

