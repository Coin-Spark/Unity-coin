
Debian
====================
This directory contains files used to package unityd/unity-qt
for Debian-based Linux systems. If you compile unityd/unity-qt yourself, there are some useful files here.

## unity: URI support ##


unity-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install unity-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your unityqt binary to `/usr/bin`
and the `../../share/pixmaps/unity128.png` to `/usr/share/pixmaps`

unity-qt.protocol (KDE)

