# Volume Steps+ 2.0 for Magisk v20.0+

## How to use:
- Open a terminal emulator app on your phone
- Write command: su
- Write command: volstep 
- Follow instructions in terminal loaded script
- For example to edit media steps value, write su => volstep => a => number (your value) => reboot => done

## Description:
### Raises the Volume Step counts to:
- In-call volume:	10 (callsteps) 
- Media volume:		25 (mediasteps)
- Set safe media bypass to false 
- You can change all these values in terminal by command: volstep

### After installing the module the below values will be added to the build.prop or default.prop file (based on your Android version):
- ro.config.vc_call_vol_steps=10
- ro.config.media_vol_steps=25
- audio.safemedia.bypass=false

## Requirements:
- Magisk 17.0 or higer
- If the module does not work for you, try install the BusyBox Magisk Module

## Warning:
- Maybe the module won't work on Samsung stock ROM!

## Tested and working on:
- Xperia XZ Oreo Stock ROM - with Magisk 17.3
- Xperia Z5 Compact LineAgeOS 14.1 - with Magisk 18.0
- OnePlus 7 Pro Stock OOS, Android 10 - with Magisk 20.4

# Changelog:
## Version 2.0
  - moving to a lower case command, volstep
  - massive code refactorisation and consolidation
  - added back option to go to main menu

## Version 1.8
  - updated module to comply with Magisk v20+
  - removed obsolete files
  - code cleanup

## Version 1.3.0 - 1.3.9
  - module code optimalization and fixes
  - support reboot from module
  - to select in menu you have multiple options for one function ect-1/a/A for media volume steps
  - write Q for exit from module script
  - if you write wrong value for apply, you can write new again
  - some little changes in texts

## Version 1.2.0 - 1.2.5
  - bug fixes
  - compatibility for Magisk GitHub Repo

## Version 1.1.1 - 1.1.2
  - just few little fixes, nothing big
  - edit of module style
  - added selection: q - for Exit
  - fixed use instructions

## Version 1.0.0
  - Initial Release 1.0(0)
