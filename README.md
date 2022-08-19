Linux Distribution Timeline | README
------------------------------------

* Copyright (C) 2010-2012 Andreas Lundqvist, Donjan Rodic, Mohammed A. Mustafa
* Copyright (C) 2016 Muhammad Herdiansyah
* Copyright (C) 2016-2021 Fabio Loli

Permission is granted to copy, distribute and/or modify this document
under the terms of the GNU Free Documentation License, Version 1.3 or
any later version published by the Free Software Foundation; with no
Invariant Sections, no Front-Cover Texts, and no Back-Cover Texts.

Original source: https://futurist.se/gldt/

Current source: https://github.com/FabioLolix/LinuxTimeline

### CONTRIBUTING

See [CONTRIBUTING](https://github.com/FabioLolix/LinuxTimeline/blob/master/CONTRIBUTING)

### Installation

If you want to build your own version, make sure you have gnuclad
installed.

> An alternative method to install gnuclad:
>
> First, download [Release 0.2.4.p1 · FabioLolix/gnuclad (github.com)](https://github.com/FabioLolix/gnuclad/releases/tag/0.2.4.p1).
> 
> ```shell
> $ unzip gnuclad-0.2.4.p1.zip
> gnuclad-0.2.4.p1 $ yum install gcc gcc-c++ automake # maybe redundant
> gnuclad-0.2.4.p1 $ ./configure
> gnuclad-0.2.4.p1 $ make
> gnuclad-0.2.4.p1 $ sudo make install
> ```

To install gnuclad, you can download the source at https://launchpad.net/gnuclad

For Arch users, use the AUR: https://aur.archlinux.org/packages/gnuclad/

After you have installed gnuclad, to build just the svg, run:

    gnuclad ldt.csv SVG ldt.conf

You can run the script `build.sh` to build the svg, png, and the tarball
containing the source, ImageMagick is required to convert from svg to png.


### Info archive

Since timeline version 21.10 all links are replaced to the correspective page 
at the info archive https://distroware.gitlab.io/

For version 20.10 all links are replaced to the correspective page 
at the info archive https://fabiololix.gitlab.io/

It is open and can be built using Mkdocs static site generator, code hosted both at

https://gitlab.com/Distroware/distroware.gitlab.io

https://github.com/FabioLolix/distroware.gitlab.io


### Projects which are not a Linux distribution

| **Projects which are not a Linux distribution** |  |
|-|-|
| [Barebox](https://www.barebox.org/) | Bootloader designed for embedded systems. It runs on a variety of architectures including x86, ARM, MIPS, PowerPC and others |
| [OpenEmbedded](https://www.openembedded.org/) | Software framework for creating embedded Linux distributions |
| [PTXdist](https://www.ptxdist.org/) | Build system for firmware images, the collection of recipes is based on GNU Make and Bash |
| [rauc](https://www.rauc.io/) | Lightweight update client that runs on your embedded Linux  |
| [Yocto Project](https://www.yoctoproject.org/) | Complete embedded Linux development environment |
|  |  |


### Related resources

https://distrowatch.com/

https://archiveos.org/linux/

https://lwn.net/Distributions/

https://www.ibiblio.org/pub/linux/distributions/

https://www.linuxlinks.com/Distributions/

https://www.debian.org/derivatives/

https://wiki.archlinux.org/index.php/Arch-based_distributions

https://fabiololix.gitlab.io/lists/RaspberryPi_OS/

## Links

- [File:Linux Distribution Timeline 21 10 2021.svg - Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Linux_Distribution_Timeline_21_10_2021.svg)
- [FabioLolix/LinuxTimeline: Linux Distributions Timeline (github.com)](https://github.com/FabioLolix/LinuxTimeline)
- [FabioLolix/gnuclad: bazaar to git conversion and import of Gnuclad. Gnuclad tries to help the environment by creating trees. It's primary use will be generating cladogram trees for the Linux and BSD distributions timeline projects (github.com)](https://github.com/FabioLolix/gnuclad)
- [gnuclad 的安装使用 - SPARK forum-星火社区 (deepinos.org)](https://www.deepinos.org/d/216-gnuclad)
