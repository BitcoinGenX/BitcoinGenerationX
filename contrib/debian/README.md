
Debian
====================
This directory contains files used to package bitcoingenxd/bitcoingenx-qt
for Debian-based Linux systems. If you compile bitcoingenxd/bitcoingenx-qt yourself, there are some useful files here.

## bitcoingenx: URI support ##


bitcoingenx-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitcoingenx-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitcoingenxqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoingenx128.png` to `/usr/share/pixmaps`

bitcoingenx-qt.protocol (KDE)

