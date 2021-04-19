# Ender3v2Precompiled
Pre compiled binaries using the Jacob Myers marlin version for E3v2, BLTouch using Z-endstop and filament sensor. (note: filament sensor can be switched on/off in the menu on the printer)

## Big shoutout to Jacob Myers
He really build the best version of Marlin for the Ender 3V2 to date.
Check his repository here: https://github.com/Jyers/Marlin/releases/tag/v1.3.0

## Not all pre-cpmpiled versions are there, like the BLTOUCH using a Z-Endstop
Jacob provides a lot of pre-compiled libraties, but it is impossible to cater every config on the planet.
I for example have my Ender 3v2 setup with a BLTOUCH using the Z-endstop. For me the 'normal' config, using all 5 pins of the dedicated BLTOUCH port gave to many random probe fails. I also at some point got a new motherboard the V4.2.7. There is a (known) issue with v4.2.2 motherboard that in some instances has bad steppendrivers, which overheat and cause layershifts. The V4.2.7 has steppendrives in a slightly different package with a bigger heatsink. For me this solved the layershift issue..
Anyway. BLTouch using the z-endstop, as even on the V4.2.7 I had random probe fails.  Using the Z-endstop completely solved this issue.

So I decided to compile this iteration using the Jyers open source marlin library and share the binaries, as not everyone is comfortable using Visual Code Studio and or editing the required files.

I compiled both for 4.2.2 and 4.2.7 (as this is a simple thing requiring only one small change in the configuration.h file).

Again, big thanks to Jacob Myer!!!
