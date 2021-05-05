# Changelog

All notable changes to the **APX Autopilot Firmware** will be documented in this file.

## [APX Firmware v11.0.94](https://github.com/uavos/public-test/releases/tag/release-11.0.94) (05/05/21)

> Branch: `main`\
> Date: `05/05/21 21:45:28`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/bf69b93d79fdf7273eac4a842729f58108db6e22...76357655d12803e81171263e5c4e9d6cd387742d)

### New Features
* landing cancel procedure stage

### Bug Fixes
* LD proc brakes off on APP vs INIT

## [APX Firmware v11.0.91](https://github.com/uavos/public-test/releases/tag/release-11.0.91) (05/04/21)

> Branch: `main`\
> Date: `05/04/21 15:49:50`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/7d285927249ac6694e7ca28eea5961f5466323be...b87343daba32e286c7a690b170801fec1425b770)

### New Features
* STBY circle adjust
* documentation files
* runway takeoff safety auto checks

### Bug Fixes
* pitch in telemetry stream packing
* att cmd limit for RC overrides
* telemetry aux data format handling

## [APX Firmware v11.0.68](https://github.com/uavos/public-test/releases/tag/release-11.0.68) (04/20/21)

> Branch: `main`\
> Date: `04/20/21 16:37:27`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/f71d93ed62b830c0fab282c7f722448442bde0dd...33d5a705dbed3cfdbef95139d2da238515d392b7)

### New Features
* controls protection on AHRS failures
* gyro and acc critical failure protection
* AHRS in-air reset
* procedures protection against AHRS failures

### Bug Fixes
* node reset configuration procedure

## [APX Firmware v11.0.62](https://github.com/uavos/public-test/releases/tag/release-11.0.62) (04/17/21)

> Branch: `main`\
> Date: `04/17/21 17:09:46`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/a7c74cc9d3921de6a867c7adcd2f8ed3db2058dc...aa1d391a59df5ab4b4a8e317bb87ead661730ad5)

### New Features
* VCP UARTs
* VCP telemetry mode
* ifc node VCP ports

### Bug Fixes
* nav gpio P1-2 fix

### Performance Enhancements
* module status inheritance
* identity module fixes
* NMT modules addressing through indexes
* vehicle identity refactoring

## [APX Firmware v11.0.50](https://github.com/uavos/public-test/releases/tag/release-11.0.50) (04/15/21)

> Branch: `main`\
> Date: `04/15/21 16:58:31`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/f2a17f03f286bc972e09b6be99973dc84b0a5ba2...4dc12f4ec7a6f8e399eb9c939fb3552fa0f208d6)

### New Features
* COM node tested

### Bug Fixes
* shell report for tasks

## [APX Firmware v11.0.48](https://github.com/uavos/public-test/releases/tag/release-11.0.48) (04/15/21)

> Branch: `main`\
> Date: `04/15/21 16:49:48`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/f2a17f03f286bc972e09b6be99973dc84b0a5ba2...0eafb250b549b17886e2c4e3e4531450e9c9e2cc)

### New Features
* COM node tested

### Bug Fixes
* shell report for tasks

## [APX Firmware v11.0.46](https://github.com/uavos/public-test/releases/tag/release-11.0.46) (04/15/21)

> Branch: `main`\
> Date: `04/15/21 13:49:31`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/f2a17f03f286bc972e09b6be99973dc84b0a5ba2...11c91d2233882a30a0165e45e575d774e61849c1)

### New Features
* COM node tested

### Bug Fixes
* shell report for tasks

## [APX Firmware v11.0.43](https://github.com/uavos/public-test/releases/tag/release-11.0.43) (04/13/21)

> Branch: `main`\
> Date: `04/13/21 19:10:38`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/3e684358e0cf7736efec3b801429aeb620334b75...0f8ae03fc3d4cabb69d50751d17efa30c1ef46c7)

### New Features
* sim app self reboot

### Bug Fixes
* conf hash auto update
* telemetry config change online update
* mission file hash
* system time t0 for sim

### Performance Enhancements
* nodes shell and modules

## [APX Firmware v11.0.19](https://github.com/uavos/public-test/releases/tag/release-11.0.19) (03/13/21)

> Branch: `main`\
> Date: `03/13/21 16:10:53`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/424c22df72e1fcdf898ad1d40f289a22170cf4ad...7b633911bd6741c85489f30e1c870f0a17853ab5)

### Optimizations
* TECS control refactoring

## [APX Firmware v11.0.17](https://github.com/uavos/public-test/releases/tag/release-11.0.17) (03/13/21)

> Branch: `main`\
> Date: `03/13/21 12:14:50`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/7bd4e2f6b38e25c8ee196dc54695d9df76d32aea...4c7dd400d61bcdf07f58bb6366cdb7d66720c60b)

### Bug Fixes
* cmd_tecs reg on landing span from config

## [APX Firmware v11.0.15](https://github.com/uavos/public-test/releases/tag/release-11.0.15) (03/11/21)

> Branch: `main`\
> Date: `03/11/21 14:12:37`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/7bd4e2f6b38e25c8ee196dc54695d9df76d32aea...df0977495b13f4335f405fb22bdafea601a4b3b1)

### Bug Fixes
* cmd_tecs reg on landing span from config

## [APX Firmware v11.0.12](https://github.com/uavos/public-test/releases/tag/release-11.0.12) (02/28/21)

> Branch: `main`\
> Date: `02/28/21 09:00:57`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/5c201c6e12ead8d4ae3616fcde6a2871305c90af...05ca7b9d3000582af1dcc804e5f7914d5798b732)

Security updates

## [APX Firmware v11.0.10](https://github.com/uavos/public-test/releases/tag/release-11.0.10) (02/21/21)

> Branch: `main`\
> Date: `02/21/21 14:49:14`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/14ef0d5569d606ad7bb12eaa63e76b2964a9de9b...86b2095853c9027db31c6e135fae03cb6f94b988)

### New Features
* controls NaN protect

### Bug Fixes
* tasks mutexes and conditional vars on linux
* no runway landing goes to STBY

## [APX Firmware v11.0.6](https://github.com/uavos/public-test/releases/tag/release-11.0.6) (02/19/21)

> Branch: `main`\
> Date: `02/19/21 22:37:28`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/71558b5a1fbe64cf79fe53219ed9631085b3e686...b0ce380c36fa907cd338215fa8951dc49e5f55aa)

### Bug Fixes
* mag sim

## [APX Firmware v11.0.2](https://github.com/uavos/public-test/releases/tag/release-11.0.2) (02/04/21)

> Branch: `main`\
> Date: `02/04/21 12:14:34`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/bf990b104296ba42b7dcb369b7446ad1dc78c98d...1c213c6e900c8c1fc6babab57665d80e3448602b)

Security updates

