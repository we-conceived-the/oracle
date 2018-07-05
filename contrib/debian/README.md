
Debian
====================
This directory contains files used to package oracled/oracle-qt
for Debian-based Linux systems. If you compile oracled/oracle-qt yourself, there are some useful files here.

## oracle: URI support ##


oracle-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install oracle-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your oracle-qt binary to `/usr/bin`
and the `../../share/pixmaps/oracle128.png` to `/usr/share/pixmaps`

oracle-qt.protocol (KDE)

