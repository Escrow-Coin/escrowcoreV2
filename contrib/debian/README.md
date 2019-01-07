
Debian
====================
This directory contains files used to package escrowd/escrow-qt
for Debian-based Linux systems. If you compile escrowd/escrow-qt yourself, there are some useful files here.

## escrow: URI support ##


escrow-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install escrow-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your escrowqt binary to `/usr/bin`
and the `../../share/pixmaps/escrow128.png` to `/usr/share/pixmaps`

escrow-qt.protocol (KDE)

