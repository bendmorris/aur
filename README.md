This script is used to download and install packages from the Arch User 
Repository. Since writing I've discovered 
[yaourt](https://aur.archlinux.org/packages/ya/yaourt/yaourt.tar.gz), which does 
even more (but is ironically an AUR package itself.)

Installation:

    cp aur /usr/bin

Usage:

    aur package_url

The package_url is the URL of the .tar.gz file containing PKGBUILD and other 
necessary files, which can be found on <https://aur.archlinux.org>.