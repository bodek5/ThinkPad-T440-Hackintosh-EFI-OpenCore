# ThinkPad-T440-Hackintosh-EFI-OpenCore
ThinkPad T440 Hackintosh EFI OpenCore 1.0.1

## What works?
* Graphicts acceleration
* Wifi
* Keyboard & TouchPad & TrackPad
* Sleep option
* USB ports
* Brightness & Volume keys
* 
* and some more

## Not Working:
* Camera (fixable)
* FingerPrint scanner
* Bluetooth (fixable)
* tell me more

## Working versions:
* Monterey (full, no bluetooth, you can try fix)
* Ventura (you must update AirportItlwm to Ventura and patch graphicts, no bluetooth, you can try fix)
* Sonoma (you must update AirportItlwm to Sonoma and patch graphicts, no bluetooth, you can try fix)
* Sequoia (you must wifi drivers (HeliPort etc) and patch graphicts, no bluetooth, you can try fix)

## Untested:
* Sonoma - i Tested ventura and Sequoia, (so i think sonoma will work)
* Tahoe (it can work but i dont tested)

## HOW TO PATCH??
Download OCLP (https://github.com/dortania/OpenCore-Legacy-Patcher/releases), move app to "Applications" folder, start this, and click "Post-Install Root Patch. My Sequoia EFI is set up to allow the patch to work, but if you do it yourself you'll need to add a few modifications to allow OCLP to get system permissions.

## Thanks to:
* [MultimediaLucaro] https://github.com/MultimediaLucario/ for base of folder
* [Dortania] https://github.com/dortania/ for OpenCore Legacy Patcher
