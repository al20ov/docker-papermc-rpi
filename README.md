# docker-papermc-rpi
My preferred PaperMC configuration for Minecraft servers on a Raspberry Pi

## Why
There seems to be a lot of mentions of Minecraft servers running on a Rapberry Pi 4, but none on the Rapberry Pi 3 and variants. With this particular docker-compose and the right OS, you'll be able to run a Minecraft server that plays relatively smoothly, loads chunks quickly with at least two players connected on a RPi 3. And of course, if you have a RPi 4, that's even better.

## Tested on
+ Raspberry Pi 3B on HypriotOS (armv7)
+ Raspberry Pi 3B on Ubuntu Server 20.04 (aarch64)
+ Raspberry Pi 4 on Fedora 33 (aarch64)

## How to run
1. Make sure you have read the EULA and agree to use this piece of software
2. `docker-compose up -d`
