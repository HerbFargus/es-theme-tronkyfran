# Tronkyfran Themes for EmulationStation

![Arcade banner](mame/art/mame_art_blur.jpg)

Theme `tronkyfran` and variations by Tronkyfran and Herb Fargus.

Based on `simple v1.4 - 03-08-2015` by © [Nils Bonenberger](http://blog.nilsbyte.de/).

For use with [EmulationStation](http://www.emulationstation.org/).

## Variations

This theme is available in 4 variations:

1. [`tronkyfran`][1]: default + full sized images (suitable for **desktops**)
2. [`tronkyfran-optimized`][2]: default + optimized images (suitable for **Retropie Pi3**)
3. [`tronkyfran-dark`][3]: dark + full sized images (suitable for **desktops**)
4. [`tronkyfran-dark-optimized`][4]: dark + optimized images (suitable for **Retropie Pi3**)

[1]: https://github.com/HerbFargus/es-theme-tronkyfran
[2]: https://github.com/HerbFargus/es-theme-tronkyfran/tree/optimized
[3]: https://github.com/HerbFargus/es-theme-tronkyfran/tree/dark
[4]: https://github.com/HerbFargus/es-theme-tronkyfran/tree/dark-optimized

## Install `tronkyfran-dark`

Close EmulationStation and run in a terminal:

    mkdir -p ~/.emulationstation/themes
    cd ~/.emulationstation/themes
    git clone https://github.com/HerbFargus/es-theme-tronkyfran.git --branch dark --single-branch tronkyfran-dark

### Update

In order to update your installed theme (if you installed with above instructions), open a terminal and run:

    git pull

## Changelog

05-10-2017
v1.6 update
- added systems:
  SEGA Saturn

29-09-2017
v1.5 update
- introduced `dark`, `optimized` and `optimized-dark` variations
- fixed info/help text colors

03-08-2015
v1.4 update
- added systems:
  SNK Neo Geo CD
  Magnavox Odyssey 2
  GCE Vectrex
  Nintendo Virtual Boy
  Bandai WonderSwan
  Bandai WonderSwan Color
  Atari Lynx
  Nintendo Family Computer
  Nintendo Super Famicom
  SEGA Genesis

- updated systems:
  SEGA Mega Drive (showed Genesis logo and text)
  MSX (wrong path to SVG)

11-29-2014
v1.3 update
- added systems:
  MSX

10-03-2014
v1.2 update
- reduced resolution of blurred images to 720p, no visible change due to the blur. This decreases the amount of used VRAM by approx. 50 percent! very good for the Raspberry Pi build of EmulationStation.
- optimized some blurred system background images where banding occurred.

08-17-2014
v1.1 update
- added systems:
  Microsoft XBox
  SEGA Saturn
  SEGA Dreamcast
  Nintendo DS
  Nintendo Wii
  Sony PlayStation
  Sony PlayStation Portable

06-16-2014
v1.0 Initial version


## Missing systems in the theme

The following platforms are using default `simple` images:

- atarijaguar
- atarijaguarcd
- dragon32
- neogeocd
- pcx68000
- virtualboy
- wii
- wonderswan
- xbox

### No emulation possible (no theme)

- n3ds
- ps3
- ps4
- psvita
- wiiu
- xbox360


## License

Creative Commons. Please see [license.txt](license.txt).

Summary of the license below:

ALLOWED:
- Share and duplicate as it is
- Edit, alter, change it

REQUIREMENTS:
- Attribution, give credit to the creator
- Indicate changes to it
- Publish the changes under the same license

PROHIBITED:   
- Commercial distribution

### Logo Notice

The used logos and trademarks are copyright of their respective owners.