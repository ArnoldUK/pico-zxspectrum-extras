# pico-zxspectrum-extras
New features and extras for pico-zxspectrum

Here are some updates to fruit-bat's [pico-zxspectrum](https://github.com/fruit-bat/pico-zxspectrum)
I've added the ability to use a real ZX Spectrum Keyboard with the Pico Spectrum Emulator.
The updated code file <code>pzx_keyscan.cpp</code> can be copied over <code>/src/picomputer/pzx_keyscan.cpp</code> and
set <code>#define REAL_ZXKEYBOARD</code> to use the new 5x8 keyboard then rebuild.

All keys are fully functional and the Emulator Menus can only be accessed via an external button connected to one of the GPIO pins.
The Menu can be navigated using the Spectrum's keyboard number keys. There are an extra 8 external buttons that can been used
for setting the Spectrum ROM boot mode and a Joystick Keyboard.

Please see the Schematic diagram for more information on GPIO pins used.

<a href="pico-zxspectrum-realkeyboard-schematic.jpg"><img src="pico-zxspectrum-realkeyboard-schematic.jpg" height="200"/>
