
Debian
====================
This directory contains files used to package latiniod/latinio-qt
for Debian-based Linux systems. If you compile latiniod/latinio-qt yourself, there are some useful files here.

## latinio: URI support ##


latinio-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install latinio-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your latinioqt binary to `/usr/bin`
and the `../../share/pixmaps/latinio128.png` to `/usr/share/pixmaps`

latinio-qt.protocol (KDE)

