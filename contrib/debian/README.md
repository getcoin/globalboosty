
Debian
====================
This directory contains files used to package globalboostd/globalboost-qt
for Debian-based Linux systems. If you compile globalboostd/globalboost-qt yourself, there are some useful files here.

## bitcoin: URI support ##


globalboost-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install globalboost-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your globalboost-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

globalboost-qt.protocol (KDE)

