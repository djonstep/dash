
Debian
====================
This directory contains files used to package eziocoind/eziocoin-qt
for Debian-based Linux systems. If you compile eziocoind/eziocoin-qt yourself, there are some useful files here.

## eziocoin: URI support ##


eziocoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install eziocoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your eziocoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/eziocoin128.png` to `/usr/share/pixmaps`

eziocoin-qt.protocol (KDE)

