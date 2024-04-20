# About FujiNetWifi Org

## What is FujiNet?

FujiNet is a multi-peripheral emulator and WiFi network device for vintage computers. The first completed hardware was for the Atari 8-Bit line of computers and development has begun for other systems (Coleco ADAM, Apple II, Commodore 64, Atari Lynx, ZX Spectrum and more) with the goal of supporting as many old systems as possible.

What sets FujiNet apart from other WiFi devices is the new Network Device (the N Device). The N device allows vintage computers that do not have enough processing power to handle TCP/IP connections themselves to talk to the modern internet over WiFi. Virtual adapters have been created for many protocols including: TCP, UDP, HTTP, FTP, TNFS, HTTPS (SSL/TLS), SSH, TELNET, WebDAV and JSON parser.

The FujiNet project is 100% completely open source, software and hardware. All code and schematics are available here.

## Our repos

Below is a table showing all the repos in this org with descriptions. Some repos are more important than others. They are listed alphabetically and show the repo name, its description (created by the author) and if it's a fork. The forks are used to pull in FujiNet related applications and code created outside this organization. They are here for ease of discovery by people using FujiNet.

## Primary Repos

Here are some important repos from the below table, arranged by their use in the project.

### Firmware Building and Flashing

* [fujinet-firmware](https://github.com/FujiNetWIFI/fujinet-firmware)

Please read  [FujiNet Bring up Docs](https://github.com/FujiNetWIFI/fujinet-firmware/wiki/Board-bring-up-for-FujiNet-Platform.IO-code) for very specific directions on software and hardware requirements for building the latest versions of the firmware.

Looking for the fujinet-platformio repo? It has been renamed to fujinet-firmware.


### Creating CONFIG apps across the supported platforms

* [fujinet-config](https://github.com/FujiNetWIFI/fujinet-config)
* [fujinet-config-tools](https://github.com/FujiNetWIFI/fujinet-config-tools)
* [fujinet-config-loader](https://github.com/FujiNetWIFI/fujinet-config-loader)

### Hardware files to build a physical FN

* [fujinet-hardware](https://github.com/FujiNetWIFI/fujinet-hardware)

### TNFS Server to host files for FN

* [spectranet](https://github.com/FujiNetWIFI/spectranet)
* [spectranet-tnfs-fuse](https://github.com/FujiNetWIFI/spectranet-tnfs-fuse)

### Create FujiNet applications across multiple platforms

* [fujinet-lib](https://github.com/FujiNetWIFI/fujinet-lib)
* [fujinet-apps](https://github.com/FujiNetWIFI/fujinet-apps)

### Run an Emulated FujiNet on your PC

 * [fujinet-pc](https://github.com/FujiNetWIFI/fujinet-pc)
 * [fujinet-emulator-bridge](https://github.com/FujiNetWIFI/fujinet-emulator-bridge)


## Table of all repos in this org

|Name                   |Description                                                                                                          |Fork |
|-----------------------|---------------------------------------------------------------------------------------------------------------------|-----|
|Adam-Arduino-Tests     |Test Programs for #FujiNet for Coleco Adam                                                                           |false|
|AppleWin               |Apple II emulator for Windows                                                                                        |true |
|atari-sio-breakout     |Breakout board for Atari SIO port using FujiNet Connectors                                                           |false|
|fastbasic              |FastBasic - Fast BASIC interpreter for the Atari 8-bit computers - adds FujiNet Support                              |true |
|fujinet-adam-cpm-lib   |Library to use FujiNet functions from CP/M                                                                           |false|
|fujinet-adam-cpm-tools |FujiNet for Coleco Adam CP/M Tools                                                                                   |false|
|fujinet-apps           |Applications for FujiNet                                                                                             |false|
|fujinet-config         |Atari side program for configuring the FujiNet device                                                                |false|
|fujinet-config-loader  |Fast Loader for Atari #FujiNet Config                                                                                |true |
|fujinet-config-tools   |Atari side programs for configuring FujiNet                                                                          |false|
|fujinet-cpm-tools      |Tools to use in #FujiNet's CP/M environment.                                                                         |false|
|fujinet-devkit-shield  |FujiNet compatible hardware that allows you to build your own using all THT components and an Espressif devkit board.|true |
|fujinet-dosxl-tools    |#FujiNet Tools for OSS DOS XL and OS/A+                                                                              |false|
|fujinet-emulator-bridge|Allows a #FujiNet device to be used from emulators such as Altirra                                                   |false|
|fujinet-firmware       |8-bit systems to ESP32 WiFi Multifunction Firmware                                                                   |false|
|fujinet-flasher        |Simple GUI tool to flash ESPs over USB (FujiNet Edition)                                                             |true |
|fujinet-hardware       |Schematics and design files for FujiNet hardware                                                                     |false|
|fujinet-high-scores    |FujiNet High Scores Repository                                                                                       |false|
|fujinet-lib            |Common Library for Platforms to use FujiNet device (network and fuji implemented)                                    |false|
|fujinet-manuals        |Repository for FujiNet Manuals                                                                                       |false|
|fujinet-mount-and-boot |Mount all drive slots, and boot.                                                                                     |false|
|fujinet-nhandler       |Atari N: Handler for FujiNet                                                                                         |false|
|fujinet-owners-manual  |                                                                                                                     |false|
|fujinet-pc             |FujiNet firmware port to Linux, MacOS and Windows                                                                    |true |
|fujinet-sd-card        |Useful tools to put onto any #FujiNet Micro SD card.                                                                 |false|
|fujinet-vm             |Packer configurations for FujiNet development environment VMs                                                        |true |
|FujiNetWIFI.github.io  |FujiNet project website                                                                                              |false|
|fujinews               |News Reader Client for FujiNet                                                                                       |false|
|Neon-Make              |Neon Compiler in C#                                                                                                  |true |
|Neon-Read              |Browser only version of Neon                                                                                         |true |
|presentations          |Presentations or other material for conferences and shows                                                            |false|
|servers                |Source to servers for games and apps that work with FujiNet                                                          |false|
|spectranet             |Ethernet for the Sinclair ZX Spectrum                                                                                |true |
|spectranet-tnfs-fuse   |Linux FUSE filesystem driver for use with the TNFS filesystem that the ZX Spectranet uses                            |true |
|tnfs-php               |tnfs functions for php and example                                                                                   |false|
|tnfsd                  |Trivial Network File System for 8 bit systems                                                                        |true |
|vcf-east-2024-classes  |Talk material from FujiNet classes at VCF East 2024                                                                  |false|
|weather                |Fork of @bocianu's weather app.                                                                                      |false|

