# Changelog

* This is a solution for the issue #285, [Replace "icon theme" logo in Preferences window #285](https://github.com/glimpse-editor/Glimpse/issues/285)
* `gimp-prefs-new-image.svg` had a misaligned and slightly disproportionate center icon and very weird and problematic alpha export behaviour. Fixed.
* `gimp-prefs-folders-icon-themes.svg` have 3 versions generated from two distinct source files. The first and unique one, the icon with Wilber in it, is legacy and maintained there for compatibility purposes. The other two are exactly the same icon but in diferent places in the folder hierarchy. They were reworked to match the Tango theme they represent.
* This directory contains a bit more than just the icon theme preview icons solution, as conformity to the Tango HIG had to be done for consistency on some other legacy Tango icons that have already been modified recently to accommodate the new, improved Glimpse logo.
* No PNGs was generated because introducing, swapping or changing this icons on the fork may be challenging and is a decision better handled by a governance member.
