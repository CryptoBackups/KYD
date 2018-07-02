
Debian
====================
This directory contains files used to package realtimed/realtime-qt
for Debian-based Linux systems. If you compile realtimed/realtime-qt yourself, there are some useful files here.

## realtime: URI support ##


realtime-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install realtime-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your realtimeqt binary to `/usr/bin`
and the `../../share/pixmaps/realtime128.png` to `/usr/share/pixmaps`

realtime-qt.protocol (KDE)

