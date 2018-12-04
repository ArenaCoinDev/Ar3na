
Debian
====================
This directory contains files used to package ar3nad/ar3na-qt
for Debian-based Linux systems. If you compile ar3nad/ar3na-qt yourself, there are some useful files here.

## ar3na: URI support ##


ar3na-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ar3na-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ar3naqt binary to `/usr/bin`
and the `../../share/pixmaps/ar3na128.png` to `/usr/share/pixmaps`

ar3na-qt.protocol (KDE)

