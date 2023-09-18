# New Features
* using auto flaps if VSI  >  VC
* UDP interface for C2
* SIM CLI for UDP configurations
* `nav.R4` base node firmware

# Bug Fixes
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

# Performance Enhancements
* `imu` integrators and flip routines
* UART irq and IMU jitter
* optimize CPU load sampler
* `HAL` `gpio` driver refactoring
* math libs update
