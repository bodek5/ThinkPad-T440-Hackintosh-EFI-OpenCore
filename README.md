# ThinkPad-T440-Hackintosh-EFI-OpenCore
ThinkPad T440 Mackintosh EFI OpenCore 1.0.1

## What works?
* Graphicts acceleration
* Wifi
* Keyboard & TouchPad & TrackPad
* Sleep option
and some more

## Not Working:
* Camera (fixable)
* FingerPrint scanner
* Bluetooth (fixable)
tell me more

## Working versions:
* Monterey (full, no bluetooth, you can try fix)
* Ventura (you must update AirportItlwm to Ventura and patch graphicts, no bluetooth, you can try fix)
* Sonoma (you must update AirportItlwm to Sonoma and patch graphicts, no bluetooth, you can try fix)
* Sequoia (you must wifi drivers (HeliPort etc) and patch graphicts, no bluetooth, you can try fix)

## Untested:
* Sonoma - i Tested ventura and Sequoia, (so i think sonoma will work)
* Tahoe (it can work but i dont tested)

## BIOS SETTINGS

SECURITY TAB:
[✓] Security Chip = Disabled
[✓] Memory Protection > Execution Prevention = Enabled
[✓] Virtualization = Enabled
[✓] Intel (R) AT Module Activation = Disabled
[✓] Computrace = Disabled
[✓] Secure Boot = Disabled
[✓] Fingerprint Reader = Disabled

STARTUP TAB:
[✓] UEFI/Legacy Boot = Both
[✓] UEFI/Legacy Priority = UEFI First
[✓] CSM Support = Yes
[✓] Boot Mode = Quick

CONFIG TAB:
[✓] Graphics Memory = 64MB or higher

## Thanks to:
