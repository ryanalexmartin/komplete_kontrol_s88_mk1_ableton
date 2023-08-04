# komplete_kontrol_s88_mk1_ableton
Ableton Live 11 integration for Komplete Kontrol S88 Mk1.
Native Instruments, please support your older devices better.

## Installation

1. Within Native Instruments Controller Editor, import the profile `ableton_komplete_kontrol_s88_mk1.ncc`, and with your S88 Mk1 in MIDI mode (Shift + Instance on the controller) make sure that the CC knobs update to show the names.  

> On Windows, Controller Editor may not see your device.  I had to plug and unplug several times, and the device's configuration updated, but Controller Editor still did not "detect" my device (but still updated it).

2. Now, create the folder `C:\Users\{USERNAME}\AppData\Roaming\Ableton\Live 11.x.x\Preferences\User Remote Scripts\Komplete Kontrol S88 Macro` on Windows, or `~/Library/Preferences/Ableton/Live 11.x.x/User Remote Scripts/Komplete Kontrol S88` on macOS.  
Copy this repository's "UserConfiguration.txt" into that folder.


## How to Use
Shift + Instance to enter MIDI mode, and make sure you have the "ableton" template name showing on your MIDI controller.

There are two pages of controls, DEVICE and FADERS.  DEVICE will control Ableton Instrument Rack macros, and Faders will control master volume and the volume of tracks 1 through 7.

## Future improvements
I'd like to get these features working again, because most of them are broken:
![Missing Features, there's a lot](https://us.v-cdn.net/6034896/uploads/PU80VDEXTH7S/screenshot-2022-05-18-at-12-23-22.png "Missing features, there's a lot.")


## Thanks

Thanks to Sanjay C for the info on how to make this work, found on this video here, with some slight modifications:  https://www.youtube.com/watch?v=i6-PR5FrnJA

Thanks to bosgood for this repository, even though it didn't work for me:  https://github.com/bosgood/ableton_komplete_kontrol_mk1
I think my repository is actually doing the same thing as bosgood's, but his presentation is better and has more detailed information.  I opted to include the .ncc configuration file directly in mine, but it's likely that when he created that repository it was not possible to save and export configuration files.
