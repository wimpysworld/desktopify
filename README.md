<h1 align="center">
  <!-- <img src=".github/logo.png" alt="Quickemu" /> -->
  <br />
  Desktopify
</h1>

<p align="center"><b>Convert Ubuntu Server for Raspberry Pi to a Desktop.</b></p>
<!-- <div align="center"><img src=".github/screenshot.png" alt="Quickemu Screenshot" /></div> -->
<p align="center">Made with 💝 for <img src="https://raw.githubusercontent.com/anythingcodes/slack-emoji-for-techies/gh-pages/emoji/tux.png" align="top" width="24" /></p>

## Introduction

Desktopify is a simple script to convert
[Ubuntu Server for the Raspberry Pi](https://ubuntu.com/download/raspberry-pi)
to one of the official Ubuntu desktop flavours.

<!-- [![Replace VirtualBox with Bash & QEMU](https://img.youtube.com/vi/AOTYWEgw0hI/0.jpg)](https://www.youtube.com/watch?v=AOTYWEgw0hI) -->

## Installation

  * Put an [Ubuntu Server image for Raspberry Pi](https://ubuntu.com/download/raspberry-pi) on a SDHC card.
  * Boot the Ubuntu Server SDHC on a Raspberry PI 2, 3 or 4.
  * Login to the Raspberry Pi; username `ubuntu` and password `ubuntu`
      * You will be prompted to change the password
  * Clone the project
      * `git clone https://github.com/wimpysworld/desktopify.git`
  * Convert the server to a desktop
    * `sudo ./desktopify -de ubuntu-mate`

### Usage

```
Usage
  ./desktopify --de <desktop environment>

Available desktop environments are
  lubuntu
  kubuntu
  ubuntu
  ubuntu-budgie
  ubuntu-kylin
  ubuntu-mate
  ubuntu-studio
  xubuntu

You can also pass the optional --oem option which will run a setup
wizard on the next boot.
```

## TODO

- [ ] Create a snap
- [ ] Install gpio tools
- [ ] Install snaps

## DONE

- [x] Enable Bluetooth
- [x] Make sure it's Ubuntu on a Pi
- [x] Make Network Manager the default backend
- [x] Prevent low power WiFi mode
- [x] Kubuntu
- [x] Lubuntu
- [x] Ubuntu
- [x] Ubuntu Budgie
- [x] Ubuntu Kylin
- [x] Ubuntu MATE
- [x] Ubuntu Studio
- [x] Xubuntu
- [x] Drop `dpkg-architecture` requirement
- [x] Optimise Ubuntu MATE (Marco) window manager
- [x] Enable initial setup
