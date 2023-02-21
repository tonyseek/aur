# AUR (Arch User Repository)

This is the [AUR](https://wiki.archlinux.org/title/Arch_User_Repository) of [Jiangge Zhang](https://github.com/tonyseek).

## How to use archlinux-repro with mirrors

```
sudo mkdir -p /etc/archlinux-repro
sudo vim /etc/archlinux-repro/repro.conf
```

The example content:

```
BOOTSTRAPMIRROR='https://geo.mirror.pkgbuild.com/iso/latest'
HOSTMIRROR='https://geo.mirror.pkgbuild.com/$repo/os/$arch'
ARCHIVEURL='https://archive.archlinux.org/packages'
```
