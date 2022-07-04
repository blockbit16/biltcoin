
Debian
====================
This directory contains files used to package biltd/bilt-qt
for Debian-based Linux systems. If you compile biltd/bilt-qt yourself, there are some useful files here.

## bilt: URI support ##


bilt-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bilt-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bilt-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

bilt-qt.protocol (KDE)

