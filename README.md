# wii-drum-high
With Nintendo Wii remote, Nunchuk and Wii Balance Board, it is easy to produce drum kit sounds from programming of their acceleration, joystick and weight data. These data can be transmitted from Wii controllers via Bluetooth to PC or Mac without Wii consoles. Wii Drum High integrates all three kinds of Wii controllers to stimulate a drum set of Hi-hat, Snare, Base drum, Crash cymbal, Ride cymbal, Mid Tom and Low Tom. Up to 4 sets of Wii remote and nunchuk can be used at the same time. (one of my colleague succeeded in connecting 5 wiimotes to a PC, but I've never tried)

This software is written in C# and utilizes Windows Presentation Foundation (or WPF) within .NET Framework 3.5 for user interface and animation. The data from wii controllers is collected using Brian Peek's WiimoteLib? API, and sound is programmed with DirectSound?

