## [midi-feeder](https://github.com/r1sc/midi-feeder)
Maps MIDI controllers to virtual joysticks.


Use MIDI controllers as extra joysticks for flight simulators and such.

Uses vJoy, so [you'll need to install that](http://vjoystick.sourceforge.net/site/)
- requires a PATH to x86 `vJoyInterface.dll` (e.g. `C:\Program Files\vJoy\x86`)  
	or copy `vJoyInterface.dll` into the folder with `MidiFeeder.exe`.

- does not detect Bluetooth MIDI devices
- does not work with other apps using MIDI devices
- maps CC to vJoy axis or button, but not a *specific* axis or button
