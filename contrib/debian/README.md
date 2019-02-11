
Debian
====================
This directory contains files used to package flined/fline-qt
for Debian-based Linux systems. If you compile flined/fline-qt yourself, there are some useful files here.

## fline: URI support ##


fline-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fline-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your flineqt binary to `/usr/bin`
and the `../../share/pixmaps/fline128.png` to `/usr/share/pixmaps`

fline-qt.protocol (KDE)

