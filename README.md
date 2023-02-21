# Project Hazi
An open-source, modular application and hardware system designed to serve as a replacement in-car entertainment system. This project is based around the Raspberry Pi platform due to it's ubiquitous nature but intended to be a system that can run atop of a generic Linux platform running Qt so that other System-on-a-Chip's (SOCs) may be supported.

### At present, the main goals of the project are to:
 - Build a core program that functions as a media player with an easy to use GUI that will work at resolutions as low as 640x480 (4:3) or 720x400 (16:9~), basically SDTV or DVD resolutions.
 - Build in support for program modules to allow an easy to configure system for supporting extra features such as CAN/LIN bus support, Bluetooth streaming/call, iPod support e.t.c. These modules ideally should be loaded as seperate files with an easy to use configuration and API support to allow one to add car model specific features like CAN bus message codes and how to convert the variables so the core program can use them.
 - Build in support to allow an external audio in to be mixed with the output.
 - Allow system sounds to be played on a seperate mono or stereo audio device if required (some cars have seperate telephone input wires).
 - Build a dynamic list of sources according to what devices are specified in the configuration files and modules and only show them if the devices are present and responding (CD changers, iPods etc, if supported by the device).
 - Allow full theme support to allow the UI to be customisable.
 - Rear view camera support with the ability to use RPi cameras or OEM LVDS cameras.
 - Ability to show reversing system rectangles from parking sensor systems using an additional add on module to define how to read these.
 - Allow the system to support both running as an additional componant (switches source from OEM system to Project Hazi) or as a total replacement system.
 
### Some possible future items but not priority at all:
 -	Android Auto/CarPlay support without extra hardware, if possible.
 -	Siri/Google Assistant support for controling radio and maybe vehicle features, if possible.
 -	Allow CarPlay/Android Auto to use vehicle based sensors and GPS signals, if present in the car and modules.
 -	GPS support with offline mapping, perhaps with navigation.
 -	Addtional video input from sources converted to DSI.
 -	WiFi hotspot using a 4G/5G modem.
