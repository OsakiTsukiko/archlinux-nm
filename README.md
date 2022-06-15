# Arch Linux NM
Base arch linux with the following packages added:
- networkmanager
- wget
- git
## Build
To build the iso you need an Arch Linux instalation and archiso installed
```bash
$ git clone https://github.com/OsakiTsukiko/archlinux-nm
$ sudo mkarchiso -v ./archlinux-nm/
# or
$ sudo mkarchiso -v -w /path/to/work_dir -o /path/to/out_dir ./archlinux-nm/
# or, if memory allows
$ sudo mkarchiso -v -w /tmp/archiso-tmp ./archlinux-nm/
```
