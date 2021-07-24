Basically this version of neofetch always returns Arch, on any system.

Don't ask me why I wasted time on this. I don't know.


![An example image showing this version of neofetch compiled and running on Manjaro Linux](https://user-images.githubusercontent.com/49426949/126865542-ee45af4d-bcce-4087-9102-59653c50e4b4.png)

^ Actually running Manjaro

* * *

Build it as you normally would (instructions stolen from the [actual repo](https://github.com/dylanaraps/neofetch)):
- `make install`
- MacOS: `make PREFIX=/usr/local install`
- Haiku: `make PREFIX=/boot/home/config/non-packaged install`
- OpenIndiana: `gmake install`
- MinGW/MSys: `make -i install`

You might have to run this as root blablabla


**Note: this __will__ replace the actual neofetch**

To revert this, just reinstall the actual neofetch with
- `sudo apt reinstall neofetch`
- `sudo pacman -S neofetch`

or whatever the equivalent is for your distro/OS
