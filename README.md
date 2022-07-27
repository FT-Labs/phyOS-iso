
</p>

<p align="center">
  <a href="https://github.com/FT-Labs"><img src="https://raw.githubusercontent.com/FT-Labs/phyOS-plymouth-base-theme/master/usr/share/plymouth/themes/phyOS/logo.png" height="128" width="128" alt="phyOS"></a>
</p>

<p align="center">
  <a href="https://patreon.com/phyOS"><img src="https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-patreon.vercel.app%2Fapi%3Fusername%3DphyOS%26type%3Dpatrons&style=flat" alt="Become a patreon for phyOS"></a>
  <a href="https://ko-fi.com/phyos"><img src="https://raw.githubusercontent.com/FT-Labs/phyOS-dwm/screenshots/screenshots/kofi.jpg" width="128" alt="Donate for pHYOS on ko-fi"></a>&nbsp;



<p align="center">
  <img src="https://img.shields.io/badge/Maintained%3F-Yes-green?style=flat-square">
  <img src="https://img.shields.io/github/downloads/FT-Labs/phyOS-iso/total?color=green">
</p>



<p align="center">
Suckless tools based minimalist and functional distribution for aesthetics and simple usage based on <a href="https://www.archlinux.org">Arch Linux</a>.
</p>

<p align="center">
  <a href="https://ftlabs.tech" target="_blank"><img alt="home" src="https://img.shields.io/badge/HOME-blue?style=flat-square"></a>
  <a href="https://wiki.ftlabs.tech" target="_blank"><img alt="wiki" src="https://img.shields.io/badge/WIKI-blue?style=flat-square"></a>
  <a href="https://ftlabs.tech/gallery" target="_blank"><img alt="screenshots" src="https://img.shields.io/badge/SCREENSHOTS-blue?style=flat-square"></a>
  <a href="https://discord.gg/UHdZ4Pzve3" target="_blank"><img alt="discord" src="https://img.shields.io/badge/DISCORD-blue?style=flat-square"></a>
  <a href="https://t.me/+MNEvm6cv9xA3OWM0" target="_blank"><img alt="telegram" src="https://img.shields.io/badge/TELEGRAM-blue?style=flat-square"></a>
</p>

#

### Latest Release


<p align="center">
  <a href="https://github.com/FT-Labs/phyOS-iso/releases/tag/1.0.1-beta" target="_blank"><img alt="release" src="https://img.shields.io/github/v/release/FT-Labs/phyOS-iso"></a>


### Verify the authenticity of the ISO

```
gpg --keyserver hkps://keys.gnupg.net --recv-keys 964FD85861C858D7
gpg --keyserver hkps://keyserver.ubuntu.com --recv-keys 964FD85861C858D7
gpg --keyserver hkp://pgp.mit.edu --recv-keys 964FD85861C858D7

gpg --verify phyOS-2022.07.27-x86_64.iso.sig
sha256sum -c phyOS-2022.07.27-x86_64.iso.sha256
```

### How to burn the iso

- You can use tools like rufus in windows, or dd for burning it from linux. Here is a basic example with dd:

```
sudo dd bs=8M if=phyOS-2022.07.27-x86_64.iso of=/dev/{sda,sdb 'check usb path with (sudo fdisk -l)'} conv=fsync oflag=direct status=progress
```
