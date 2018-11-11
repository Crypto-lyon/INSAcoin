
Debian
====================
This directory contains files used to package insacoind/insacoin-qt
for Debian-based Linux systems. If you compile insacoind/insacoin-qt yourself, there are some useful files here.

## insacoin: URI support ##


insacoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install insacoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your insacoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

insacoin-qt.protocol (KDE)

