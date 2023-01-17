# pico-zxspectrum-extras
New features and extras for pico-zxspectrum

Here are some updates to fruitbat's pico-zxspectrum project.
I've added the ability to use a real ZX Spectrum Keyboard with the Pico Spectrum Emulator.
The updated code can be found in pzx_keyscan.cpp where a define can be set <code>#define REAL_ZXKEYBOARD</code>
to enable the updated 5x8 keyboard matrix. All keys are fully functional and the Emulator Menus can only be
accessed via an external button connected to one of the GPIO pins. The Menu can be navigated using the Spectrum's
keyboard number keys. Please see the Schematic diagram for more information on GPIO pins used.

<a href="pico-zxspectrum-realkeyboard-schematic.jpg"><img src="pico-zxspectrum-realkeyboard-schematic.jpg" height="200"/>
