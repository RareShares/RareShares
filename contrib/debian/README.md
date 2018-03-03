
Debian
====================
This directory contains files used to package raresharesd/rareshares-qt
for Debian-based Linux systems. If you compile raresharesd/rareshares-qt yourself, there are some useful files here.

## rareshares: URI support ##


rareshares-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rareshares-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rareshares-qt binary to `/usr/bin`
and the `../../share/pixmaps/rareshares128.png` to `/usr/share/pixmaps`

rareshares-qt.protocol (KDE)

