# Changelog

All notable changes to the **APX Autopilot Firmware** will be documented in this file.

## [APX Firmware v11.2.16](https://github.com/uavos/apx-ap/releases/tag/release-11.2.16) (10/27/25)

> Branch: `main`\
> Date: `10/27/25 12:46:36`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/2f124c971ca0a5a2c8a74bba6ae90a2637010948...d78a50c59442601140b867507b0618628dc38d08)

### New Features
* baro reset command

### Bug Fixes
* reference point updated for takeoff proc

## [APX Firmware v11.2.15](https://github.com/uavos/apx-ap/releases/tag/release-11.2.15) (10/25/25)

> Branch: `main`\
> Date: `10/25/25 03:26:54`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/b16af442e4aaca1613cdc702db5bd55e91e27e96...11032f2f6b4934163348ded6f28e6e30d99785cc)

### New Features
* reg L1 lateral acceleration bias
* lateral_acc() method to class RegHdg
* humidity sensor

### Bug Fixes
* wpt switch trigger timeout
* orbits counter ontrack behavior
* velocity limit
* conf for svmf1
* ADC for swmf1
* config for RS422
* wasm pool size for f4
* I2C slave address

### Comments

**feat: humidity sensor**

Driver for humidity sensor implemented

## [APX Firmware v11.2.14](https://github.com/uavos/apx-ap/releases/tag/release-11.2.14) (10/14/25)

> Branch: `geofence`\
> Date: `10/14/25 20:58:19`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/8535f79f0de723251a4ac98780b5c6b7e6f7cfec...13bf60bfdfb76a2fcbd085dcc1f4631c833e1fb6)

### New Features
* geofence mission elements

### Bug Fixes
* derivative angle
* status pitot heater
* course derivative

## [APX Firmware v11.2.13](https://github.com/uavos/apx-ap/releases/tag/release-11.2.13) (10/01/25)

> Branch: `main`\
> Date: `10/01/25 14:58:24`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/61240279333c5ecb5e907a2e8feace95207aa2cb...4853ad37f50bed953919da20e3ff6f526ad987d9)

### Bug Fixes
* config rx/tx for uart

## [APX Firmware v11.2.12](https://github.com/uavos/apx-ap/releases/tag/release-11.2.12) (09/25/25)

> Branch: `main`\
> Date: `09/25/25 23:27:38`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/3eaa8664f4d5cf12e345837fcc0417c77c356a50...3e527c2d7bda5840b35a0fb1fbfead2ea1d68e3a)

### New Features
* nogps initial wind input from GCS

### Bug Fixes
* reset wind

### Administration and Chores
* update subproject commit reference

## [APX Firmware v11.2.11](https://github.com/uavos/apx-ap/releases/tag/release-11.2.11) (09/08/25)

> Branch: `main`\
> Date: `09/08/25 19:35:55`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/20ca056c939609b0e05d44d3b6e95698dc10b2f3...05b04d2be46a33904346027751c7d7d9fb89f716)

### New Features
* allow out of range values for PWM outputs

### Bug Fixes
* control of set temperature
* proc heater

## [APX Firmware v11.2.10](https://github.com/uavos/apx-ap/releases/tag/release-11.2.10) (08/30/25)

> Branch: `main`\
> Date: `08/30/25 15:13:03`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/a9f384627e3ce1b7fd8ea2dd1732204e44a90c4f...a430c5f4f35c35a6251749c288fe8f3f91aafbf7)

### New Features
* WASM task scheduling and delays
* config for ghanta node has been added

### Bug Fixes
* nomag option sub
* hrt timer PLH1
* identity block request pids
* wasm `time_ms` native u32 wrapping
* ATS module
* canas ID
* check timeout for EstPitot and EstAgl
* report uplink timeout
* sub timeout checking
* canas protocol
* adjust radius for POI
* adjust radius
* PubSub for status

## [APX Firmware v11.2.9](https://github.com/uavos/apx-ap/releases/tag/release-11.2.9) (06/03/25)

> Branch: `main`\
> Date: `06/03/25 19:53:48`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/eefcf5cf70198f73d406ff3643e8da43934bb635...f4a5ed9e0188ab410cc810891f017da46357830e)

### New Features
* dev blocking by error rate

### Bug Fixes
* slip control at low ground speed
* build nav R41
* xcan filter rx
* warning  for gps RS1
* mag calibration pkt routing
* disconnect mission
* include module
* debug FDCAN

## [APX Firmware v11.2.8](https://github.com/uavos/apx-ap/releases/tag/release-11.2.8) (05/06/25)

> Branch: `main`\
> Date: `05/06/25 11:56:18`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/26b028d20c4615a7ff82bf1fbd7161563e5ec02b...051a9260a81ede29d5c30ba8ac45d482b3d7e4ea)

### New Features
* temp sensors via adc

### Bug Fixes
* request timeout in mdb
* request data for PubConnection
* temp imu icm42688
* event sub connection
* gain ktas
* landing on missing runway behavior
* voltage mode for ADC
* check local data
* local pub bind
* transform setpoint to body angular rates

### Performance Enhancements
* remove old async mission signals

## [APX Firmware v11.2.7](https://github.com/uavos/apx-ap/releases/tag/release-11.2.7) (03/24/25)

> Branch: `main`\
> Date: `03/24/25 21:08:24`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/5ea835a01001c9e6185f2414538c31627e7ffa6f...c1c31be9863be0c6f316ec2ea50e36e0bd7268cc)

### Bug Fixes
* min tc for yaw reg

## [APX Firmware v11.2.6](https://github.com/uavos/apx-ap/releases/tag/release-11.2.6) (01/27/25)

> Branch: `main`\
> Date: `01/27/25 18:22:44`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/b8099a272277f0af95aeb694e11b567926dbb73b...885399eda1f2bc6bd9b7c3c81f860e9642fdab54)

### Bug Fixes
* use cmd roll in coordinated turn rate bias control

### Performance Enhancements
* fully static sub via template

## [APX Firmware v11.2.5](https://github.com/uavos/apx-ap/releases/tag/release-11.2.5) (01/16/25)

> Branch: `main`\
> Date: `01/16/25 21:28:32`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/dd2e30efcb0042b4dbd5a3821771f402bcd827d7...9354463b01f3848ea7a0d80dcf1b032988d25631)

### Bug Fixes
* no mission warning message
* Takeoff cancel if no runway
* remove repeated console messages on missing takeoff runway
* STBY min radius for VTOL

### Performance Enhancements
* atomize regulators
* Pub via template

## [APX Firmware v11.2.4](https://github.com/uavos/apx-ap/releases/tag/release-11.2.4) (01/08/25)

> Branch: `main`\
> Date: `01/08/25 21:01:50`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/db4c8bd731643653754e06ed85291d89f6af6e16...c668df699d0140754332a9729456542ea1135d7e)

### New Features
* altitude tracking wpt navigation mode

### Bug Fixes
* protect LD/TO/TAXI modes from fly-to-here GCS commands

### Performance Enhancements
* wp switch behavior refactoring

## [APX Firmware v11.2.3](https://github.com/uavos/apx-ap/releases/tag/release-11.2.3) (01/06/25)

> Branch: `main`\
> Date: `01/06/25 19:18:43`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/9fc07f42fea2083c0f0128d847d559059440ec71...982b18d0d9726b3ca8b62b0dfc78840a4c24518e)

Security updates

## [APX Firmware v11.2.2](https://github.com/uavos/apx-ap/releases/tag/release-11.2.2) (12/23/24)

> Branch: `main`\
> Date: `12/23/24 19:27:56`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/620f71878c65b3bc8e98c9e0bc83df8b71b845a9...11c487f730da404ce37100fdd53e0fea2b2f66a2)

### New Features
* mag reset command
* EKF status reporting

### Bug Fixes
* estimator init
* axis for mmc5983
* mag declination for sim

## [APX Firmware v11.2.1](https://github.com/uavos/apx-ap/releases/tag/release-11.2.1) (12/19/24)

> Branch: `main`\
> Date: `12/19/24 08:57:20`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/09fd64d1d2d2a0cd2662b300c768ad2f461b2e13...738de43e3b73669387236169f4c645f2b988d13d)

### Bug Fixes
* pitot estimator time

## [APX Firmware v11.2.0](https://github.com/uavos/apx-ap/releases/tag/release-11.2.0) (12/07/24)

> Branch: `main`\
> Date: `12/07/24 11:28:47`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/193b6f7ecb7d4f3898a88c3feb5d9a354f768be3...5c084f82a8b781893741ebc26efab3628326d8ad)

### New Features
* user data from xplane to sim

### Bug Fixes
* trim zero for yaw
* type for trim zero
* distance to vehicle

### Performance Enhancements
* mdb Sub as static class template
* mdb static lists

## [APX Firmware v11.1.26](https://github.com/uavos/apx-ap/releases/tag/release-11.1.26) (08/08/24)

> Branch: `main`\
> Date: `08/08/24 14:54:08`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/347798c88beaa53056b64637eabf25bec6fd5861...a517b9b2d6eb6481ca760727f6472c79922c6e15)

### Bug Fixes
* invalid samples for icm42688
* reading FIFO for icm42688
* VOLZ protocol
* reset ekf

## [APX Firmware v11.1.25](https://github.com/uavos/apx-ap/releases/tag/release-11.1.25) (06/19/24)

> Branch: `main`\
> Date: `06/19/24 20:57:27`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/41afc26c373276eb4879fca97ba9f2ef3d4b158f...1351da7865e197a5209f89d713093b732561cf9d)

### New Features
* WPT mode wp passed signal via `stage=1`
* script vmexec with arg

### Bug Fixes
* XPDR and telemetry refactoring
* MAVEV vmexec via NAMED_VALUE_FLOAT
* MAVEV go WPT mode from STBY on MISSION_SET_CURRENT

## [APX Firmware v11.1.24](https://github.com/uavos/apx-ap/releases/tag/release-11.1.24) (05/23/24)

> Branch: `main`\
> Date: `05/23/24 17:30:05`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/547c014952208f96e94ff1ee0d22d6c577c93c05...018181a5f5ba7f503f32567f22becda0d2bca1a7)

### Bug Fixes
* ahrs & shiva config updaters
* HRT timer scheduler bug
* HRT timer scheduler bug
* ahrs & shiva config updaters

## [APX Firmware v11.1.23](https://github.com/uavos/apx-ap/releases/tag/release-11.1.23) (05/21/24)

> Branch: `main`\
> Date: `05/21/24 22:37:22`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/dc525cc67c7057b137df48012d19d55285c53f8c...9d7272876b0e97e54b8874e6cbc764f64c8e6ed4)

### New Features
* safety datalink timeout

### Bug Fixes
* publishers schedule
* GPIO LLD events init don't touch pin config

## [APX Firmware v11.1.22](https://github.com/uavos/apx-ap/releases/tag/release-11.1.22) (05/19/24)

> Branch: `main`\
> Date: `05/19/24 18:28:55`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/0055e7bbe4487fcb7d95fcb5b4e55c69c8afea0c...dedb9902b893f1254cf951c5818d992733cda4f3)

### Bug Fixes
* `SPI` over `DMA` for `H7`
* MAVEV mission controls
* TECS min speed
* HUB interfaces mutual exclusion
* MDB publisher init
* publishers thread safety

## [APX Firmware v11.1.21](https://github.com/uavos/apx-ap/releases/tag/release-11.1.21) (05/12/24)

> Branch: `main`\
> Date: `05/12/24 20:01:23`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/4a591f866d3009bd5a27d9da2a481c99e33f8494...33134c70df0aad01ff6dc3fc72feea39fcafea21)

### New Features
* MAVLINK mission control
* VTOL fly to hover transitions
* heli hover velocity control

### Bug Fixes
* AHRS default tune
* Telemetry mode for VCP
* maneuvers logic
* VTOL low speed TECS
* AHRS airdata mode fix (wind speed)
* feed forward for governor
* min prop for kff
* landing height source option

## [APX Firmware v11.1.20](https://github.com/uavos/apx-ap/releases/tag/release-11.1.20) (05/07/24)

> Branch: `main`\
> Date: `05/07/24 09:18:23`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/b9793139f7aea6a92fdc33f9316dc70e63712430...6d35447d6ff889e94a02b275fcecdb60a67483bf)

### Bug Fixes
* sim macos universal binary

## [APX Firmware v11.1.19](https://github.com/uavos/apx-ap/releases/tag/release-11.1.19) (05/06/24)

> Branch: `main`\
> Date: `05/06/24 20:22:28`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/754b1475713297391da828ddf04021f9110d0f16...8df665ec5e5d4cb054e87728e7cafa2cbe26a77c)

### Bug Fixes
* dataset for telemetry
* MAVLINK byte re-ordering
* dataset for telemetry
* init PWM
* xusb TX error messages when disconnected
* silent disabled `protocols` module children
* Wind Estimator for VTOL
* validate all binded controls in mixer on init
* Wind Estimator for VTOL
* gspeed enables AHRS airdata
* use VSI for AHRS airdata for VTOL
* helipad landing speed control
* protocols module enabled check
* add VPS variances

### Performance Enhancements
* gpio mixer fixes

## [APX Firmware v11.1.18](https://github.com/uavos/apx-ap/releases/tag/release-11.1.18) (04/10/24)

> Branch: `main`\
> Date: `04/10/24 11:08:03`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/32f93f41c176fd5310c09bc78b0a78c308db3deb...28495ea7c204e33645113772041e97b5d0824fa2)

### New Features
* shock/busy CPU test commands

### Bug Fixes
* VCP rx fifo ovf handling
* stop bits conf options
* VCP rx fifo full errors spam
* MAVLINK HEARTBEAT stream
* MAV_MODE_FLAG_SAFETY_ARMED by default is true
* MAV base_status msg flags

## [APX Firmware v11.1.17](https://github.com/uavos/apx-ap/releases/tag/release-11.1.17) (03/25/24)

> Branch: `main`\
> Date: `03/25/24 15:08:05`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/03be0ee051e4943169d82cc6700c26c8d2b5a7c8...7b99b1af37ef2310218296a6f5083cf7cb9b3923)

### Bug Fixes
* `MAVLINK` TIMESYNC units (nanosec)
* MAVLINK packets reception on multiple consecutive messages

## [APX Firmware v11.1.16](https://github.com/uavos/apx-ap/releases/tag/release-11.1.16) (03/19/24)

> Branch: `fix-heli-turns`\
> Date: `03/19/24 21:43:55`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/c19d3e86a27a81aeb50b61f5a4e8fe7b93f72992...72b82a7dd1ba968adb0724cd29b3f36246f33477)

### New Features
* airspeed control refactoring for VTOL

### Bug Fixes
* VCP reconfiguration and bundle sub duplicates check
* VTOL hover transitions (exit to HDG)
* climb/sink rate gains

## [APX Firmware v11.1.15](https://github.com/uavos/apx-ap/releases/tag/release-11.1.15) (03/12/24)

> Branch: `main`\
> Date: `03/12/24 12:39:03`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/1bd86961ff8f5260281bbb11c18b8aee9f9e5c8f...20d926b6112823b5e154ed6ea8f60ec4cbfd5201)

### Bug Fixes
* raw GPS velocities for MAVLINK msg

## [APX Firmware v11.1.14](https://github.com/uavos/apx-ap/releases/tag/release-11.1.14) (03/11/24)

> Branch: `main`\
> Date: `03/11/24 20:02:09`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/d1b0786c690b0baf2905962abbb0487de1c29b5f...f34f01bb98da25208b636e25d9787342917d63e4)

### New Features
* conf parameters for yaw control coordinated turns

### Bug Fixes
* coordinated turn `VSO` bottom limit
* contstraints for `slip` and `roll` for turns
* conf fields refactoring

## [APX Firmware v11.1.13](https://github.com/uavos/apx-ap/releases/tag/release-11.1.13) (02/26/24)

> Branch: `main`\
> Date: `02/26/24 14:09:00`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/ac7b4676e9242d2db1e4639b823a0910f7df03f7...528e2686f38dfc218220d5a20222b136d2e89d41)

### Bug Fixes
* `nav.R4` 16kHz IMU timing
* drop first IMU reads after reset
* `nav.R4` MAVLINK protocols

## [APX Firmware v11.1.12](https://github.com/uavos/apx-ap/releases/tag/release-11.1.12) (02/23/24)

> Branch: `main`\
> Date: `02/23/24 09:01:05`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/7d740ac4f9030e1d8b8b2e2758340a471cfbf994...677200511cbc37d024ba459ff9228c40bc53708a)

### Bug Fixes
* pos state for landing
* MMC5983 DRDY pull up
* `mmc5983` mag body frame
* configure pwm
* condition for limit cmd_roll
* title in vcp
* quantity channels for r4 node

## [APX Firmware v11.1.11](https://github.com/uavos/apx-ap/releases/tag/release-11.1.11) (02/01/24)

> Branch: `main`\
> Date: `02/01/24 09:14:59`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/a9566bff5cd859f3a082f979f4d00fa46ff9a1fb...daa8058c9e934f249aacbd2ae868004eae54a200)

### New Features
* bias for sim data

### Bug Fixes
* `SPI` over `DMA` for `H7`
* `Ubuntu 20.04 LTS` release build for `SIM` node
* protocols FIFO
* posix stack size constraints
* xudp task config temporary
* RS485 de re

### Performance Enhancements
* wasm build optimizations

## [APX Firmware v11.1.10](https://github.com/uavos/apx-ap/releases/tag/release-11.1.10) (11/20/23)

> Branch: `main`\
> Date: `11/20/23 16:28:45`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/03c62fa73cedb8322736160653282641ddea1cf0...ecfed254ead9ca1b45804ee2a8a8e4f8136164a2)

### New Features
* bias for sim data
* `VCP` receiver timeout packetization

### Bug Fixes
* UART timeout based receiver

## [APX Firmware v11.1.9](https://github.com/uavos/apx-ap/releases/tag/release-11.1.9) (11/10/23)

> Branch: `main`\
> Date: `11/10/23 09:00:52`\
> Diff: [uavos/apx-fw](https://github.com/uavos/apx-fw/compare/af2f476491ed4d1e6963672799b58220395a9831...511d481231d54fe6d07fd745e6fcd93579d30b06)

Security updates

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

