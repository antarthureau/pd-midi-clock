# pd-midi-clock
A puredata clock per pulse from an external MIDI source

A midi port/input is necessary on the computer. One can use a MIDI to USB interface, or pull the MIDI clock from any DAW like Ableton, Reaper, etc..
To create a virtual MIDI port on a computer one can use loopmidi (https://www.tobias-erichsen.de/software/loopmidi.html) on Windows
or setup a virtaual port on macOS (https://support.apple.com/en-gb/guide/audio-midi-setup/ams1013/mac)

This patch uses the object "counter", from the cyclone library. Therefore, it needs the library to be installed in order to run. It is also possible
to bypass that object and make an equivalent with Pd vanilla's set of objects.
