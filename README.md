<p align="center">
  <a href="https://github.com/FT-Labs"><img src="https://raw.githubusercontent.com/FT-Labs/phyOS-plymouth-base-theme/master/usr/share/plymouth/themes/phyOS/logo.png" height="256" width="256" alt="phyOS"></a>
</p>

<p align="center">
  <a href="https://patreon.com/phyOS"><img src="https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-patreon.vercel.app%2Fapi%3Fusername%3DphyOS%26type%3Dpatrons&style=flat" alt="Become a patreon for phyOS"></a>
  <a href="https://ko-fi.com/phyos"><img src="https://raw.githubusercontent.com/FT-Labs/phyOS-dwm/screenshots/screenshots/kofi.jpg" width="128" alt="Donate for pHYOS on ko-fi"></a>&nbsp;

<p align="center">
  <a href="https://github.com/FT-Labs/phyOS-iso/releases" target="_blank"><img src="https://img.shields.io/github/downloads/FT-Labs/phyOS-iso/total?color=green"></img></a>
  <a href="https://github.com/FT-Labs/phyOS-iso/commits/master" target="_blank"><img src="https://img.shields.io/github/commit-activity/w/FT-Labs/phyOS-iso"></img></a>
  <a href="https://github.com/FT-Labs/phyOS-iso/releases" target="_blank"><img src="https://img.shields.io/github/v/release/FT-Labs/phyOS-iso?color=%23ffa500"></a>
  <a href="https://github.com/FT-Labs/phyOS-iso/issues?q=is%3Aissue+is%3Aclosed" target="_blank"><img src="https://img.shields.io/github/issues-closed-raw/FT-Labs/phyOS-iso"></a>
</p>

<p align="center">
<a href="https://suckless.org/">Suckless</a> tools based minimalist and functional distribution for aesthetics and simple usage based on <a href="https://www.archlinux.org">Arch Linux</a>.
</p>
<p align="center">
First LVM2 and LUKS2 supported arch based distribution. Automatic initcpio hooks to unlock crypted root partition.
</p>
<hr>
<p align="center">PLEASE JOIN OUR DISCORD SERVER FOR GUIDES AND RECENT UPDATES.</p>

<p align="center">
  <!-- <a href="https://ftlabs.tech" target="_blank"><img alt="home" src="https://img.shields.io/badge/HOME-blue?style=flat-square"></a> -->
  <!-- <a href="https://wiki.ftlabs.tech" target="_blank"><img alt="wiki" src="https://img.shields.io/badge/WIKI-blue?style=flat-square"></a> -->
  <!-- <a href="https://ftlabs.tech/gallery" target="_blank"><img alt="screenshots" src="https://img.shields.io/badge/SCREENSHOTS-blue?style=flat-square"></a> -->
  <a href="https://discord.gg/UHdZ4Pzve3" target="_blank"><img alt="discord" src="https://img.shields.io/badge/DISCORD-blue?style=flat-square"></a>
  <a href="https://t.me/+MNEvm6cv9xA3OWM0" target="_blank"><img alt="telegram" src="https://img.shields.io/badge/TELEGRAM-blue?style=flat-square"></a>
</p>

## <p align="center">Verify the authenticity of the ISO</p>

```
gpg --keyserver hkps://keys.gnupg.net --recv-keys 964FD85861C858D7
gpg --keyserver hkps://keyserver.ubuntu.com --recv-keys 964FD85861C858D7
gpg --keyserver hkp://pgp.mit.edu --recv-keys 964FD85861C858D7

gpg --verify phyOS-2022.10.12-x86_64.iso.sig
sha256sum -c phyOS-2022.10.12-x86_64.iso.sha256
```

## <p align="center">How to burn the iso</p>

| App                                     | Platform        | Instructions                                                                                                                                 |
|-----------------------------------------|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| [Rufus](http://rufus.ie)                | Windows         | Make sure to choose DD Image mode when prompted                                                                                              |
| [Etcher](https://www.balena.io/etcher/) | Cross platform  | -                                                                                                                                            |
| [Ventoy](https://www.ventoy.net)        | Cross platform  | -                                                                                                                                            |
| DD command                              | Linux & Mac ClI | `sudo dd bs=8M if=phyOS-2022.10.12-x86_64.iso of=/dev/{sda,sdb 'check usb path with (sudo fdisk -l)'} conv=fsync oflag=direct status=progress` |

<hr>

## <p align="center">Features</p>

### <p align="center">PhyOS System Settings Application</p>
<p align="center">Tweak your settings and customization, choose animations. Look at the source code over here -> <a href="https://github.com/FT-Labs/pdwmc">pdwmc</a></p>

## <p align="center">Screenshots</p>
<hr>
<img src="https://github.com/FT-Labs/phyOS-dwm/blob/screenshots/screenshots/setting-1.png">
<img src="https://github.com/FT-Labs/phyOS-dwm/blob/screenshots/screenshots/setting-2.png">
<img src="https://github.com/FT-Labs/phyOS-dwm/blob/screenshots/screenshots/setting-3.png">
<img src="https://github.com/FT-Labs/phyOS-dwm/blob/screenshots/screenshots/setting-4.png">
