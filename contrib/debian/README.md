
Debian
====================
This directory contains files used to package tecaxd/tecax-qt
for Debian-based Linux systems. If you compile tecaxd/tecax-qt yourself, there are some useful files here.

## tecax: URI support ##


tecax-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tecax-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tecax-qt binary to `/usr/bin`
and the `../../share/pixmaps/tecax128.png` to `/usr/share/pixmaps`

tecax-qt.protocol (KDE)

