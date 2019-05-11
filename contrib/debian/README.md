
Debian
====================
This directory contains files used to package awardcoind/awardcoin-qt
for Debian-based Linux systems. If you compile awardcoind/awardcoin-qt yourself, there are some useful files here.

## awardcoin: URI support ##


awardcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install awardcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your awardcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/awardcoin128.png` to `/usr/share/pixmaps`

awardcoin-qt.protocol (KDE)

