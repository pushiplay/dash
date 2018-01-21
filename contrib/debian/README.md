
Debian
====================
This directory contains files used to package pushid/pushi-qt
for Debian-based Linux systems. If you compile pushid/pushi-qt yourself, there are some useful files here.

## pushi: URI support ##


pushi-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pushi-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pushi-qt binary to `/usr/bin`
and the `../../share/pixmaps/pushi128.png` to `/usr/share/pixmaps`

pushi-qt.protocol (KDE)

