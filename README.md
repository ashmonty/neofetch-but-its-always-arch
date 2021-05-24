Basically this version of neofetch always returns Arch, on any system.

![image](https://user-images.githubusercontent.com/49426949/119331499-b3ea0f80-bc87-11eb-8b47-df3988f79ed8.png)

^ actually running Kubuntu

* * *

Build it as you normally would:
- `make install`
- MacOS: `make PREFIX=/usr/local install`
- Haiku: `make PREFIX=/boot/home/config/non-packaged install`
- OpenIndiana: `gmake install`
- MinGW/MSys: `make -i install`

You might have to run this as root blablabla

**Note: this __will__ replace the actual neofetch**
To revert this, just `sudo apt reinstall neofetch` or whatever is the equivalent for your distro
