
Debian
====================
This directory contains files used to package kydcoind/kydcoin-qt
for Debian-based Linux systems. If you compile kydcoind/kydcoin-qt yourself, there are some useful files here.

## kydcoin: URI support ##


kydcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install kydcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your kydcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/kydcoin128.png` to `/usr/share/pixmaps`

kydcoin-qt.protocol (KDE)

