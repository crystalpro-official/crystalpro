
Debian
====================
This directory contains files used to package crystalprod/crystalpro-qt
for Debian-based Linux systems. If you compile crystalprod/crystalpro-qt yourself, there are some useful files here.

## crystalpro: URI support ##


crystalpro-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install crystalpro-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your crystalproqt binary to `/usr/bin`
and the `../../share/pixmaps/crystalpro128.png` to `/usr/share/pixmaps`

crystalpro-qt.protocol (KDE)

