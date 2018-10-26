
Debian
====================
This directory contains files used to package decentroniumd/decentronium-qt
for Debian-based Linux systems. If you compile decentroniumd/decentronium-qt yourself, there are some useful files here.

## decentronium: URI support ##


decentronium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install decentronium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your decentroniumqt binary to `/usr/bin`
and the `../../share/pixmaps/decentronium128.png` to `/usr/share/pixmaps`

decentronium-qt.protocol (KDE)

