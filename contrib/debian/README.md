
Debian
====================
This directory contains files used to package Gigad/Giga-qt
for Debian-based Linux systems. If you compile Gigad/Giga-qt yourself, there are some useful files here.

## Giga: URI support ##


Giga-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Giga-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your Gigaqt binary to `/usr/bin`
and the `../../share/pixmaps/Giga128.png` to `/usr/share/pixmaps`

Giga-qt.protocol (KDE)

