# tuxedo-plymouth-one
TUXEDO style plymouth theme

## Screenshot & GIF
![Screenshot TUXEDO One](https://raw.github.com/tuxedocomputers/tuxedo-plymouth-one/master/screenshot.png?raw=true "Screenshot TUXEDO One")
![Preview TUXEDO One](https://raw.github.com/tuxedocomputers/tuxedo-plymouth-one/master/preview.gif?raw=true "Preview TUXEDO One")

## How to use

* ``cd /usr/share/plymouth/themes/``
* ``sudo git clone https://github.com/tuxedocomputers/tuxedo-plymouth-one.git tuxedo-one``
* ``sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/tuxedo-one/tuxedo-one.plymouth 100``
* ``sudo update-alternatives --config default.plymouth``
* ``sudo update-initramfs -u -k all``

## Authors
* Written by: Alberto Milone <alberto.milone@canonical.com>
* Adapted to budgie-remix by: HEXcube <hexcubed@gmail.com> and David Mohammed <foss.freedom@gmail.com>
* Adapted to TUXEDO Computers by: Vinzenz Vietzke <tux@tuxedocomputers.com>
* Based on the example provided with the "script plugin" written by Charlie Brej <cbrej@cs.man.ac.uk>
* Question stuff written by Markus Waas <mail@markuswaas.de>
