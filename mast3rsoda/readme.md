# Leaf65

![Leaf65](imgur.com image replace me!)

Custom leaf65 firmware I wrote and use after not being able to find the Foxlab one.

* Keyboard Maintainer: [Mast3rSoda](https://github.com/Mast3rSoda)
* Hardware Supported: Leaf65 Hotswap PCB
* Hardware Availability: Lmao long gone

## FYI the below was not tested

Make example for this keyboard (after setting up your build environment):

    make leaf65:Mast3rSoda:default or make leaf65:Mast3rSoda:via

Flashing example for this keyboard:

    make leaf65:Mast3rSoda:default:flase or make leaf65:Mast3rSoda:via

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
