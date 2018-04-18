
Debian
====================
This directory contains files used to package charmd/charm-qt
for Debian-based Linux systems. If you compile charmd/charm-qt yourself, there are some useful files here.

## charm: URI support ##


charm-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install charm-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your charm-qt binary to `/usr/bin`
and the `../../share/pixmaps/charm128.png` to `/usr/share/pixmaps`

charm-qt.protocol (KDE)

