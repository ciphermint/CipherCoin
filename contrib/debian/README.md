
Debian
====================
This directory contains files used to package ciphercoind/ciphercoin-qt
for Debian-based Linux systems. If you compile ciphercoind/ciphercoin-qt yourself, there are some useful files here.

## ciphercoin: URI support ##


ciphercoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ciphercoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ciphercoinqt binary to `/usr/bin`
and the `../../share/pixmaps/ciphercoin128.png` to `/usr/share/pixmaps`

ciphercoin-qt.protocol (KDE)

