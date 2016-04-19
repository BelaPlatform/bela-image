# bela-image
Images to flash on your BeagleBone Black for use with the Bela cape.

No source code at the moment, only zipped versions of the SD card image available for download. Check the Releases section

## Getting started

Download the Bela SD card image from the Releases link above.
There currently are two different releases available, one stable and one testing.

The stable release runs the basic Debian Wheezy distro with Xenomai extensions, with kernel Linux arm 3.8.13xenomai-bone41. It contains all the toolkits needed to compile and run Bela projects.

The testing release is the same as the stable but with a few additional packages which we installed through the Jessie repositories: gcc-4.9 and clang-3.6.

Uncompress the image using *xz* (which you may have to install) and flash it onto the SD card.
For instructions on how to do so, check out the [wiki page](https://github.com/BelaPlatform/bela-image/wiki)
An SD card of at least 2GB is required for the stable release and at least 8GB for the testing release.



