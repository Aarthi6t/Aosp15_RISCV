
# AOSP 15 RISC-V QEMU

AOSP 15 Android build and development environment for **RISC-V using QEMU**.

## Overview

This project contains work related to:

* Android 15 AOSP
* RISC-V 64-bit architecture
* QEMU virtual platform
* Kernel and device configuration
* Android system bring-up and testing

## Build

```bash
source build/envsetup.sh
lunch <target>
m -j$(nproc)
```

## Run

The generated Android images can be used with a compatible RISC-V QEMU configuration.

## Status

🚧 Development in progress.

## Repository

**AOSP 15 | RISC-V | QEMU | Android**
