# Yocto-Based Embedded Linux System with Multithreaded TCP Server & Character Device Driver

An embedded Linux system built using Yocto featuring a multithreaded TCP socket server, a custom Linux character device driver with circular buffer support, and ARM64 image generation for QEMU.

## Features

- Custom Yocto layer and recipes
- Multithreaded TCP server using POSIX threads, runs as a daemon
- Custom Linux character device (Circular Buffer) and its driver implementation
- `ioctl()` support for indexing into the device
- init scripts for driver and server
- ARM64 image generation and QEMU testing
- Automated build and test workflow

## Author

Raj
