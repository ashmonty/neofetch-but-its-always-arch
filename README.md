Basically this version of neofetch always returns Arch, on any system.

Don't ask me why I wasted time on this. I don't know.

![An example image showing this version of neofetch compiled and running on Manjaro Linux](https://user-images.githubusercontent.com/49426949/120924572-af384900-c6d4-11eb-81fb-bde122157acb.png)

^ actually running Manjaro

* * *

Build it as you normally would:
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
