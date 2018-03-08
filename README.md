This .so file is designed to support the Qualcomm OEM commands.

## To Build
```
To build this package, do the following steps:

    1. ./bootstrap.sh
    2. ./configure ${CONFIGURE_FLAGS}
    3. make

To full clean the repository again run `./bootstrap.sh clean`.
```

## Supported Commands
- Set Boot Mode
- Get Boot Mode
- Get Pcie Slot Status
- Get BMC Vendor
- Get Fan PWM
- Set Fan Speed
- Node ID Detection
- Board ID Detection
- Send SoC MAC
- Get Platform MAC
