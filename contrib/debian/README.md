
Debian
====================
This directory contains files used to package econocalypsed/econocalypse-qt
for Debian-based Linux systems. If you compile econocalypsed/econocalypse-qt yourself, there are some useful files here.

## econocalypse: URI support ##


econocalypse-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install econocalypse-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your econocalypseqt binary to `/usr/bin`
and the `../../share/pixmaps/econocalypse128.png` to `/usr/share/pixmaps`

econocalypse-qt.protocol (KDE)

