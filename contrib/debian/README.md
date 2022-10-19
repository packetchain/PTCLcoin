
Debian
====================
This directory contains files used to package ptclcoind/ptclcoin-qt
for Debian-based Linux systems. If you compile ptclcoind/ptclcoin-qt yourself, there are some useful files here.

## ptclcoin: URI support ##


ptclcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ptclcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ptclcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/ptclcoin128.png` to `/usr/share/pixmaps`

ptclcoin-qt.protocol (KDE)

