# Plunge Drone Software
## // ON READY PART

### Software for local plunge drone controller.
### Based on open-source project [OpenROV](https://github.com/OpenROV)

### Description from original [repository](https://github.com/OpenROV/openrov-software-arduino):
#### Important:
This version of the firmware no longer works with Cockpit versions 30.0.3 or earlier. The infrastructure to build and flash this code only exists in cockpit 31.0.1 and later.
Description

Contains sketches, configuration files, and build/upload scripts for the OpenROV Controller Board. The sketches are built automatically by the ArduinoBuilder library in the cockpit project and can currently only be easily built using that process.

Eventually this project will become a GCC Makefile project to facilitate easy, cross-platform builds and automated testing.

The code is organized in the following manner:

    bin: contains pre-compiled binaries distributed with our images, such as ESC firmware. Built firmware also gets installed here.
    libraries: contains libraries and modules shared across MCU architectures and sketches
    libraries_wip: libraries that still need to be made cross-architecture
    scripts: helper scripts for working with the source. Currently contains astyle presets for the project
    sketches: MCU application source. These are not guaranteed to be cross-architecture/board compatible.

Currently, the firmware that runs on the OpenROV 2X controllerboard can be found in sketches/OpenROV2x/

#### Style
Please use one of the astyle scripts in the scripts directory to automatically format your source before submitting PRs.

#### Issues
For submitting issues use the primary software repository: https://github.com/OpenROV/openrov-software/issues

## // IN DEV PART
Software for control and communicate with drone.
Will be used next stact: 
* c++ programming language
* QT framework
* win2sock.h (for Windows platform)
* socket.h (for Linux platform)

Interface references:

![alt text](https://github.com/PolyPlunge/pdsoft/blob/main/images/refer.png)
