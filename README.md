# eTodo-releases
Prebuilt release packages for Linux, Mac and Windows and other files needed to build these packages.

The packages are built for the following architectures:

* Windows 32-bit
* Windows 64-bit
* Ubuntu 64-bit (will probably work on most debian package based distributions)
* Mac 64-bit

If the packages don't work for you build your own release using the eTodo repository.

Command to build ubuntu package:

dpkg-deb --build build/

On Mac use disk-utils to make a new dmg file.

1. Convert old eTodo.dmg to use no encryption and read/writable.
2. Copy built release into dmg file.
3. Convert back to no encryption and compressed.

On Windows NSIS is used to build package from zip file.


