<h1 align="center">
  <!-- <img src=".github/logo.png" alt="Quickemu" /> -->
  <br />
  Desktopify
</h1>

# This project is discontinued ☠️

**This project initially served as a PoC for bringing [Ubuntu Desktop to Raspberry Pi](https://www.omgubuntu.co.uk/2020/10/ubuntu-20-10-raspberry-pi-4-desktop) when I worked at [Canonical](https://canonical.com/). Now that [Raspberry Pi is a release target for Ubuntu Desktop](https://ubuntu.com/download/raspberry-pi), this project has no purpose.** 

<p align="center"><b>Convert Ubuntu Server for Raspberry Pi to a Desktop.</b></p>
<!-- <div align="center"><img src=".github/screenshot.png" alt="Quickemu Screenshot" /></div> -->
<p align="center">Made with 💝 for <img src=".github/ubuntu.png" align="top" width="18" /></p>

## Introduction

Desktopify is a simple script to convert
[Ubuntu Server for the Raspberry Pi](https://ubuntu.com/download/raspberry-pi)
to one of the official Ubuntu desktop flavours.

We have a Discord for this project: [![Discord](https://img.shields.io/discord/712850672223125565?color=0C306A&label=WimpysWorld%20Discord&logo=Discord&logoColor=ffffff&style=flat-square)](https://discord.gg/hy7uZfX)

[![Raspberry Pi 4 8GB - Install Ubuntu Desktop 20.04 LTS](https://img.youtube.com/vi/umtZuUJOU38/0.jpg)](https://www.youtube.com/watch?v=umtZuUJOU38)

## Installation

  * Put an [Ubuntu Server image for Raspberry Pi](https://ubuntu.com/download/raspberry-pi) on a SDHC card.
  * Boot the Ubuntu Server SDHC on a Raspberry Pi 2, 3 or 4.
  * Login to the Raspberry Pi; username `ubuntu` and password `ubuntu`
      * You will be prompted to change the password
  * Clone the project
    * `git clone https://github.com/wimpysworld/desktopify.git`
  * Change your current directory to desktopify directory
    * `cd desktopify`
  * Convert the server to a desktop
    * `sudo ./desktopify --de ubuntu-mate`

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

- [ ] Emoji status

## DONE

- [x] Install GPIO utilities and libraries
- [x] Enable Bluetooth
- [x] Make sure it's Ubuntu on a Pi
- [x] Make Network Manager the default backend
- [x] Prevent low power WiFi mode
- [x] Disable overscan
- [x] Enable fkms driver
- [x] Enable boot splash
- [x] Enable Firefox hardware acceleration
- [x] Create a snap
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
- [x] Prevent pointless re-installs
- [x] Install snaps
- [x] Install gpio tools
