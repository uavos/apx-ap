# Changelog

All notable changes to the **APX Autopilot Firmware** will be documented in this file.

## [APX Firmware v11.1.8](https://github.com/uavos/apx-ap/releases/tag/release-11.1.8) (11/05/23)

> Branch: `main`\
> Date: `11/05/23 16:43:22`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/76a9d9d14ce0f272f197fa0dc51ec51a3c9f1b40...ed9b8c912a366a9cd9a072ef1719c0c5f09fdcd2)

### Performance Enhancements
* WASM engine upgrade

## [APX Firmware v11.1.7](https://github.com/uavos/apx-ap/releases/tag/release-11.1.7) (09/17/23)

> Branch: `main`\
> Date: `09/17/23 18:49:46`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/57127e417f5c319dac45a8e909149f6a86dc33d6...ca811019306ccd846e8420f9fd7807ac6efc0023)

### New Features
* using auto flaps if VSI  >  VC
* UDP interface for C2
* SIM CLI for UDP configurations
* `nav.R4` base node firmware

### Bug Fixes
* block_rc in pitch
* AuxController
* mutex unlock
* Air brake controller
* circles count in STBY mode
* STBY mode timeout
* airbrk controller
* flaps controller
* descr in VSI speed
* touchdown stage
* touchdown and flare stage
* RC mode
* PWM in NAV module
* PWM in MHX module
* can in F7
* matrix scalar operators (sub,div)
* SPI baud rate configuration
* perf load int math rounding fix
* `flash lld` driver F7/F4 large fw upload blocks
* SPI multiple bus devices DMA config bug `important`
* driver for lsm9ds1
* LSM9DS1 flip axis
* description PWM
* merge file
* bias in GPIO
* type for custom literal
* SBUSRX

### Performance Enhancements
* `imu` integrators and flip routines
* UART irq and IMU jitter
* optimize CPU load sampler
* `HAL` `gpio` driver refactoring
* math libs update

## [APX Firmware v11.1.96](https://github.com/uavos/apx-ap/releases/tag/release-11.1.96) (08/06/22)

> Branch: `main`\
> Date: `08/06/22 17:27:47`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/92acda4f75b6403d74b07e0961b5d443d9d6f4e2...5b624aa9059800e3b2d2dac40d81d540a9d7687f)

### New Features
* telemetry slots auto requests

### Bug Fixes
* PWM in com.DLF1
* mandala reports values init
* L1 track mode waypoints triggers (closes [`2`](https://github.com/uavos/apx-ap/issues/2))
* ATS module

### Performance Enhancements
* telemetry streams and auto sync
* binary search for telemetry streamer
* static subs

## [APX Firmware v11.1.60](https://github.com/uavos/apx-ap/releases/tag/release-11.1.60) (03/22/22)

> Branch: `dev`\
> Date: `03/22/22 17:36:15`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/b538ca57f55b107c5374adf7ff47ac9a28231d58...d3ad5203edacca4b71341815b8a280d29ff3938f)

### Bug Fixes
* launcher procedure

### Performance Enhancements
* EKF upgrade
* Matrix math update
* AHRS magnetometer faults mgmt

## [APX Firmware v11.1.52](https://github.com/uavos/apx-ap/releases/tag/release-11.1.52) (03/16/22)

> Branch: `main`\
> Date: `03/16/22 00:06:48`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/5380d38c0e13ddb56cc6f2e8c129f26ab6f77b53...a1acb5666ac8739cf9218d48efc3a1357287ee95)

### New Features
* new range of cas sensors
* JetCat protocol
* analog input module
* ktas gain
* power ap on and pwr check on takeoff

### Bug Fixes
* PWM in ifc device
* mux config in ifc
* ktas gain
* JetCat protocol
* WASM serial port packet size

## [APX Firmware v11.1.51](https://github.com/uavos/apx-ap/releases/tag/release-11.1.51) (03/16/22)

> Branch: `main`\
> Date: `03/16/22 00:06:21`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/1c5886267480e0d5e97e29ddf26b2c69da4443f7...fbf4d126090b43515c057899f3a6368b2d7a0df4)

Security updates

## [APX Firmware v11.1.49](https://github.com/uavos/apx-ap/releases/tag/release-11.1.49) (03/15/22)

> Branch: `main`\
> Date: `03/15/22 23:46:33`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/c6a42e28a4a0b78a4242c2c7a4dc602a98400eb7...3092175cc3cff188763cef538917aa85f73b7159)

Security updates

## [APX Firmware v11.1.47](https://github.com/uavos/apx-ap/releases/tag/release-11.1.47) (03/15/22)

> Branch: `main`\
> Date: `03/15/22 22:03:37`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/5380d38c0e13ddb56cc6f2e8c129f26ab6f77b53...eb52de02bba0996bcc0784cf398a6b1f762b12d3)

### New Features
* new range of cas sensors
* JetCat protocol
* analog input module
* ktas gain
* power ap on and pwr check on takeoff

### Bug Fixes
* PWM in ifc device
* mux config in ifc
* ktas gain
* JetCat protocol
* WASM serial port packet size

## [APX Firmware v11.1.21](https://github.com/uavos/apx-ap/releases/tag/release-11.1.21) (02/11/22)

> Branch: `main`\
> Date: `02/11/22 20:08:46`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/ed3251cc6dca84d618f3226d087533c7adcf3a4f...0d7736a7492464949cc9a09cad9b8298947b1691)

### New Features
* com-DLF1 board introduction and HW mappings
* MMC5983 magnetometer driver
* VCP UARTs as Identity links

## [APX Firmware v11.1.19](https://github.com/uavos/apx-ap/releases/tag/release-11.1.19) (02/11/22)

> Branch: `main`\
> Date: `02/11/22 19:59:37`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/ed3251cc6dca84d618f3226d087533c7adcf3a4f...cae0f603be2252182c1277b1b7b4c2f07615e21e)

### New Features
* com-DLF1 board introduction and HW mappings
* MMC5983 magnetometer driver
* VCP UARTs as Identity links

## [APX Firmware v11.1.6](https://github.com/uavos/apx-ap/releases/tag/release-11.1.6) (02/04/22)

> Branch: `ekf`\
> Date: `02/04/22 16:21:38`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/3136ea4501cf9d3b07eab96da4d7aaf7a8b0ee01...08ecdb2f61b725ac83c3347289b6afb74d53bff7)

### Performance Enhancements
* apx-math removal, better math for EKF

## [APX Firmware v11.1.1](https://github.com/uavos/apx-ap/releases/tag/release-11.1.1) (01/29/22)

> Branch: `main`\
> Date: `01/29/22 20:16:15`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/b89829ecb064554b8045f0df38f40d4c2e7ff061...9e2e015ee76939f288adf41ae0dbdedf81582c13)

### New Features
* heli hover regulators
* heli hover transitions
* engine governor with procedures
* engine regulator procedures
* engine warning est
* heli hover climb/sink limits
* sim vehicle UID by callsign ([`22`](https://github.com/uavos/apx-ap/issues/22))
* sim bias airspeed sensor

### Bug Fixes
* TAS for Energy estimations
* LANDING pattern estimators
* L1 loiter near circle center
* ProcTO launcher and STBY
* imu sensor orientation in gps

### Performance Enhancements
* shiva controllers refactoring

## [APX Firmware v11.0.122](https://github.com/uavos/apx-ap/releases/tag/release-11.0.122) (05/20/21)

> Branch: `main`\
> Date: `05/20/21 17:04:48`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/bf83564214f01fa53d668d34441d8272dd356bf7...bdbe2002e6b269a834a0352c5965233c0d745d11)

### New Features
* uptime telemetry provider
* AHRS mutex protection
* fuel estimator
* WASM vmexec requests support
* fuel sensor processing

### Bug Fixes
* mission online update for WPT, LD, TO
* throttle cut behavior on takeoff
* inner loops validation and config check

## [APX Firmware v11.0.105](https://github.com/uavos/apx-ap/releases/tag/release-11.0.105) (05/08/21)

> Branch: `main`\
> Date: `05/08/21 16:19:08`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/8c8cdaa061a58af1cadaab6d9510aa18e85feec1...f6663e3d6a5bd270639723c8649c5f3c0da457fb)

### New Features
* TECS altitude priority operation (TO/LD)
* throttle block option on landing finished
* slip estimator with sensors data
* stability estimator
* stability gains and trims for attitude controllers
* U-turns optimization option
* mission item select commands for WPT and TAXI

### Bug Fixes
* bearing management for L1 controllers

## [APX Firmware v11.0.94](https://github.com/uavos/apx-ap/releases/tag/release-11.0.94) (05/05/21)

> Branch: `main`\
> Date: `05/05/21 21:45:28`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/bf69b93d79fdf7273eac4a842729f58108db6e22...76357655d12803e81171263e5c4e9d6cd387742d)

### New Features
* landing cancel procedure stage

### Bug Fixes
* LD proc brakes off on APP vs INIT

## [APX Firmware v11.0.91](https://github.com/uavos/apx-ap/releases/tag/release-11.0.91) (05/04/21)

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

## [APX Firmware v11.0.68](https://github.com/uavos/apx-ap/releases/tag/release-11.0.68) (04/20/21)

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

## [APX Firmware v11.0.62](https://github.com/uavos/apx-ap/releases/tag/release-11.0.62) (04/17/21)

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

## [APX Firmware v11.0.50](https://github.com/uavos/apx-ap/releases/tag/release-11.0.50) (04/15/21)

> Branch: `main`\
> Date: `04/15/21 16:58:31`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/f2a17f03f286bc972e09b6be99973dc84b0a5ba2...4dc12f4ec7a6f8e399eb9c939fb3552fa0f208d6)

### New Features
* COM node tested

### Bug Fixes
* shell report for tasks

## [APX Firmware v11.0.48](https://github.com/uavos/apx-ap/releases/tag/release-11.0.48) (04/15/21)

> Branch: `main`\
> Date: `04/15/21 16:49:48`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/f2a17f03f286bc972e09b6be99973dc84b0a5ba2...0eafb250b549b17886e2c4e3e4531450e9c9e2cc)

### New Features
* COM node tested

### Bug Fixes
* shell report for tasks

## [APX Firmware v11.0.46](https://github.com/uavos/apx-ap/releases/tag/release-11.0.46) (04/15/21)

> Branch: `main`\
> Date: `04/15/21 13:49:31`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/f2a17f03f286bc972e09b6be99973dc84b0a5ba2...11c91d2233882a30a0165e45e575d774e61849c1)

### New Features
* COM node tested

### Bug Fixes
* shell report for tasks

## [APX Firmware v11.0.43](https://github.com/uavos/apx-ap/releases/tag/release-11.0.43) (04/13/21)

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

## [APX Firmware v11.0.19](https://github.com/uavos/apx-ap/releases/tag/release-11.0.19) (03/13/21)

> Branch: `main`\
> Date: `03/13/21 16:10:53`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/424c22df72e1fcdf898ad1d40f289a22170cf4ad...7b633911bd6741c85489f30e1c870f0a17853ab5)

### Optimizations
* TECS control refactoring

## [APX Firmware v11.0.17](https://github.com/uavos/apx-ap/releases/tag/release-11.0.17) (03/13/21)

> Branch: `main`\
> Date: `03/13/21 12:14:50`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/7bd4e2f6b38e25c8ee196dc54695d9df76d32aea...4c7dd400d61bcdf07f58bb6366cdb7d66720c60b)

### Bug Fixes
* cmd_tecs reg on landing span from config

## [APX Firmware v11.0.15](https://github.com/uavos/apx-ap/releases/tag/release-11.0.15) (03/11/21)

> Branch: `main`\
> Date: `03/11/21 14:12:37`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/7bd4e2f6b38e25c8ee196dc54695d9df76d32aea...df0977495b13f4335f405fb22bdafea601a4b3b1)

### Bug Fixes
* cmd_tecs reg on landing span from config

## [APX Firmware v11.0.12](https://github.com/uavos/apx-ap/releases/tag/release-11.0.12) (02/28/21)

> Branch: `main`\
> Date: `02/28/21 09:00:57`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/5c201c6e12ead8d4ae3616fcde6a2871305c90af...05ca7b9d3000582af1dcc804e5f7914d5798b732)

Security updates

## [APX Firmware v11.0.10](https://github.com/uavos/apx-ap/releases/tag/release-11.0.10) (02/21/21)

> Branch: `main`\
> Date: `02/21/21 14:49:14`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/14ef0d5569d606ad7bb12eaa63e76b2964a9de9b...86b2095853c9027db31c6e135fae03cb6f94b988)

### New Features
* controls NaN protect

### Bug Fixes
* tasks mutexes and conditional vars on linux
* no runway landing goes to STBY

## [APX Firmware v11.0.6](https://github.com/uavos/apx-ap/releases/tag/release-11.0.6) (02/19/21)

> Branch: `main`\
> Date: `02/19/21 22:37:28`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/71558b5a1fbe64cf79fe53219ed9631085b3e686...b0ce380c36fa907cd338215fa8951dc49e5f55aa)

### Bug Fixes
* mag sim

## [APX Firmware v11.0.2](https://github.com/uavos/apx-ap/releases/tag/release-11.0.2) (02/04/21)

> Branch: `main`\
> Date: `02/04/21 12:14:34`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/bf990b104296ba42b7dcb369b7446ad1dc78c98d...1c213c6e900c8c1fc6babab57665d80e3448602b)

Security updates

