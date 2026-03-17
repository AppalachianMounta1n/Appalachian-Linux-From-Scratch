# Appalachian-Linux-From-Scratch
I've started LFS a few times but never got too far into it, so this is going to be a repository for me going through the [stable systemd](https://www.linuxfromscratch.org/lfs/view/stable-systemd/) version of the project. I will be looking into updating to [Beyond Linux From Scratch](https://www.linuxfromscratch.org/blfs/) once I finish the base project.

I am to follow the [POSIX.1-2024](https://standards.ieee.org/ieee/1003.1/7700/), [Filesystem Hierarchy Standard](https://refspecs.linuxfoundation.org/FHS_3.0/fhs/index.html), and [Linux Standard Base 5.0](https://refspecs.linuxfoundation.org/lsb.shtml) standards, making modifications where necessary to update from the listed POSIX1.2008 standard.

## Extra Packages
These packages are not provided by LFS or BLFS and will be added at the conclusion of both to satisfy Linux Standard Base requirements.
- install_initd
- libcrypt.so.1

These packages will not be added as they are older versions of existing libraries.
- libncurses.so.5
- libncursesw.so.5
- libgdk-x11-2.0.so
- libgtk-x11-2.0.so
- libgpng12.so
- libQt*.so.4
- libtiff.so.4
- libpng15.s0

I will be including both Python2 and Python 3 installations.