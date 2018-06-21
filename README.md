[![Build Status](https://travis-ci.org/libretro/picodrive.svg?branch=master)](https://travis-ci.org/libretro/picodrive)
[![Build status](https://ci.appveyor.com/api/projects/status/a1a66rbxe3600mrd/branch/master?svg=true)](https://ci.appveyor.com/project/bparker06/picodrive/branch/master)

This is yet another Megadrive / Genesis / Sega CD / Mega CD / 32X / SMS
emulator, which was written having ARM-based handheld devices in mind
(such as smartphones and handheld consoles like GP2X and Pandora),
but also runs on non-ARM little-endian hardware too.

The emulator is heavily optimized for ARM, features assembly cores for
68k, Z80 and VDP chip emulation, also has dynamic recompilers for SH2 and
SSP16 (for 32X and SVP emulation). It was started by Dave (aka fdave,
finalburn author) as basic Genesis/Megadrive emulator for Pocket PC,
then taken over and expanded by notaz.

PicoDrive was the first emulator ever to properly emulate Virtua Racing and
it's SVP chip.
