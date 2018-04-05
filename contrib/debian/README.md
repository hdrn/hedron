
Debian
====================
This directory contains files used to package hedrond/hedron-qt
for Debian-based Linux systems. If you compile hedrond/hedron-qt yourself, there are some useful files here.

## hedron: URI support ##


hedron-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hedron-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hedronqt binary to `/usr/bin`
and the `../../share/pixmaps/hedron128.png` to `/usr/share/pixmaps`

hedron-qt.protocol (KDE)

