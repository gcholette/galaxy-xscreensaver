# galaxy-xscreensaver
Updated version of the galaxy screensaver with supplementary arguments and customisation.

To use, copy the released executable into /usr/lib/xscreensaver as `galaxy` (in the releases tab in github)

You can test it by running `./galaxy -count -3 -maxStars 5000 -minSize 0.1 -maxSize 0.75`

Incremental development has to be done inside the xscreensaver code source since there are multiple dependencies I don't want to include here.

Please refer to https://github.com/Zygo/xscreensaver for the code source (mirror to the newer versions) for further development; I also have a fork https://github.com/showlet/xscreensaver-edit of the 5.42 release.

