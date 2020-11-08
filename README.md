# Budgie Network Applet (Debian Packaging)
This is a fork of [Budgie Network Applet](https://github.com/danielpinto8zz6/budgie-network-applet), adding Debian Packaging and some more features

## Building and Installation

Use `apt install devscripts libgtk-3-dev libpeas-dev budgie-core-dev valac libnm-dev libnma-dev meson` to install the Build dependencies

    sudo apt install devscripts libgtk-3-dev libpeas-dev budgie-core-dev valac libnm-dev libnma-dev meson

Run `debuild` to build the Debian Package

    debuild

To install, use `apt install ../budgie-network-applet*.deb`

    sudo apt install ../budgie-network-applet*.deb
