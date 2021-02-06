# Pico setup for Windows

[Download the latest release](https://github.com/ndabas/pico-setup-windows/releases)

This project aims to create an easy-to-use installer to get started (using the C/C++ SDK) with the [Raspberry Pi Pico](https://www.raspberrypi.org/products/raspberry-pi-pico/) microcontroller board, and possibly other RP2040-based boards as well. It is inspired by, and is roughly equivalent to, the [pico-setup](https://github.com/raspberrypi/pico-setup) project for Linux systems.

The installers automate the prerequisite installation on Windows, as explained in the official [Getting started with Raspberry Pi Pico](https://datasheets.raspberrypi.org/pico/getting-started-with-pico.pdf) guide. In addition, the installer offers to clone and build the Raspberry Pi Pico SDK for C/C++, along with some related repos which might be useful.

Documentation for end-users is in the [ReadMe.txt](docs/ReadMe.txt) file that is copied by the installer.

The installers attempt to install the required tools silently, without user intervantion. The installers are configured with the recommended options from the official guide. For advanced users who wish to configure the software themselves, it might be better to download and install the software manually, or using a package manager.

## Included software

- [GNU Arm Embedded Toolchain](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm/downloads) - the official guide refers to this as "ARM GCC Compiler"
- [CMake](https://cmake.org/download/)
- [Build Tools for Visual Studio 2019](https://visualstudio.microsoft.com/downloads/#build-tools-for-visual-studio-2019)
- [Python 3.8](https://www.python.org/downloads/windows/)
- [Git for Windows](https://git-scm.com/download/win)