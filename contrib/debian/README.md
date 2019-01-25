
Debian
====================
This directory contains files used to package proxd/prox-qt
for Debian-based Linux systems. If you compile proxd/prox-qt yourself, there are some useful files here.

## prox: URI support ##


prox-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install prox-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your proxqt binary to `/usr/bin`
and the `../../share/pixmaps/prox128.png` to `/usr/share/pixmaps`

prox-qt.protocol (KDE)

