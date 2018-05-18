
Debian
====================
This directory contains files used to package essenced/essence-qt
for Debian-based Linux systems. If you compile essenced/essence-qt yourself, there are some useful files here.

## essence: URI support ##


essence-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install essence-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your essence-qt binary to `/usr/bin`
and the `../../share/pixmaps/essence128.png` to `/usr/share/pixmaps`

essence-qt.protocol (KDE)

