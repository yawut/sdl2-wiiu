
    SDL2 / SDL2_gfx / SDL2_image / SDL2_ttf for Nintendo Wii U


Prerequisites
---
The following tools must be installed:
- devkitPPC
- WUT
- portlibs (the wiiu version, available at dimok789's homebrew_launcher release page)

The following path variables must be exported:
- $WUT_ROOT
- $DEVKITPRO
- $DEVKITPPC


Install
---
Run the following, from this repo's root directory:

cd SDL2-wiiu
make -f Makefile.wiiu install
cd ..

cd SDL2_image-2.0.3-wiiu
make -f Makefile.wiiu install
cd ..

cd SDL2_gfx-1.0.4-wiiu
make -f Makefile.wiiu install
cd ..

cd SDL2_ttf-2.0.14-wiiu
make -f Makefile.wiiu install
cd ..


Credits
---
The SDL2 port is based on exjam's threads and timers libraries
and inspired on sdl-libtransistor