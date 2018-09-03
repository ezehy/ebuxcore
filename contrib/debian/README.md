
Debian
====================
This directory contains files used to package ebuxd/ebux-qt
for Debian-based Linux systems. If you compile ebuxd/ebux-qt yourself, there are some useful files here.

## ebux: URI support ##


ebux-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ebux-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ebuxqt binary to `/usr/bin`
and the `../../share/pixmaps/ebux128.png` to `/usr/share/pixmaps`

ebux-qt.protocol (KDE)

