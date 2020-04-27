---
title: "ArduPilot Based Setup"
permalink: /docs/ardupilot/
---

Work In Progress

**CAUTION -- NO PROPS.  Not needed.  Put them in a drawer until we get ready to fly. 

## Initial Setup
### Bind RX
- Bind RX to TX per manufacturer instructions.  OpenTX an FrSky X8R

### Load ArduPilot Firmware
- Connect MP to PixRacer via USB
- Load latest stable firmware. ArdcuCopter 4.0.3 
- Reboot

### Mandatory Hardware
- Connect MP to PixRacer via USB
#### Radio Calibration
 Radio Cal per wiki.  Note pitch input - it might need to be reversed in radio.

### Break For Serial Assignments
- Insert table of PixRacer uart to serial here
- config/tuning>>full params>>search "serialx" where x is serial number
- Update each serial per table; save params; reboot; might (should?) start getting telemetry to Yaapu script

### Resume Mandatory Hardware
#### Accel and compass
- per wiki
- Reboot 
- Check Flight Data HUD for heading.
#### Failsafes
 Set and check Failsafe per wiki.  We only use RC but enable and configure per local regulations.
#### Flight Modes 
- Leave Flight Modes to all stabilize for now.  Will set them during Preflight.

### Optional Hardware
#### Batt Mon
- Analog Voltage and Current; Other; etc ; [insert ss]
- Plug in flight battery and check values in HUD.  Wiki for more?

### Break for Motor Setup
- Wiki Pages
- MOT_PWM_TYPE = 4 = DShot
- SERVO_BLH_AUTO = 1
- SERVO_BLH_POLES = 12 (per your motor specs)
- SERIAL5_PROTOCOL = 16 (ESC telem but we set it at the start; just check it)
- Reboot

Note that DShot does not require ESC calibration

### Resume Optional Hardware

#### Motor Test
- Plug in flt battery
- Connect telem
- Initial Setup >> Optional Hardware >> Motor Test

Note - Motor assigments A-D ARE NOT THE SAME as the motor 1-4 number assignements.  See wiki page.  Front right first; then move in clockwise fashion.

- Press and hold Safety Switch to allow motor arming
- Test each motor and note rotation per the wiki image

### Break for BLHeli
- Disconnect MP or anything else using serial ports
- Follow wiki.  Using BLHeli Suite 32710 Change rotations as required.  Also a good time to update firmware.  32.7 as of this writing 

### Resume Optional Hardware

#### Motor Test
- This time we will use the radio
- Flt battery
- Move throttle stick to bottom right and hold until armed
- Motors should spin slowly
- See wiki for tweaking motor spin when armed etc

#### Range Finder (LiDAR) 
- Per Wiki
- MAX 600
- CLEAR 5
- Make sure to verify per wiki


### Advanced Configuration
https://ardupilot.org/copter/docs/common-advanced-configuration.html

#### Harmonic Notch
- Per wiki but it's a bit confusing.  Only need to make two changes when using ESC Telem:
- INS_HNTCH_MODE = 3
- INS_HNTCH_REF = 1

#### Tuning Params
- Per Tuning Prcess Instructions wiki
- Pull from charts on wiki page or use spreadsheet here:  https://discuss.ardupilot.org/t/new-tuning-instructions-wiki-page/44953/53

#### Logging Params
- Prefernce to have new log saved after disarmed LOG_FILE_DSRMROT = 1
- For troubleshooting Log bitmask etc per wiki

## Full Param Files
- Link to pre autotune
- Link to post autotune








