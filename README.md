MDMBlock
==============

[![Build Status](https://github.com/flagersgit/MDMBlock/workflows/CI/badge.svg?branch=master)](https://github.com/flagersgit/MDMBlock/actions)

[Lilu](https://github.com/acidanthera/Lilu) Kernel extension for blocking unwanted MDM notifications. The list of blocks currently includes:

- `/System/Library/CoreServices/ManagedClient.app/Contents/Resources/ManagedClientAgent`
- `/usr/libexec/mdmclient`

#### Boot arguments
- `-mdmboff` (or `-liluoff`) to disable
- `-mdmbdbg` (or `-liludbgall`) to enable verbose logging (in DEBUG builds)
- `-mdmbbeta` (or `-lilubetaall`) to enable on macOS older than 10.8 or newer than 12
- `-mdmbproc` to enable verbose process logging (in DEBUG builds)

#### Credits
- [Apple](https://www.apple.com) for macOS  
- [vit9696](https://github.com/vit9696) for [Lilu.kext](https://github.com/vit9696/Lilu) and for [RestrictEvents.kext](https://github.com/acidanthera/RestrictEvents) which is the basis for this project.
