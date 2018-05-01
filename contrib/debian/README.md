
Debian
====================
This directory contains files used to package checkcashd/checkcash-qt
for Debian-based Linux systems. If you compile checkcashd/checkcash-qt yourself, there are some useful files here.

## checkcash: URI support ##


checkcash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install checkcash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your checkcash-qt binary to `/usr/bin`
and the `../../share/pixmaps/checkcash128.png` to `/usr/share/pixmaps`

checkcash-qt.protocol (KDE)

