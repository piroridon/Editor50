# Editor50

"Editor50" is 40% keyboard designed for text editing, equipped with a four-way stick switch, two rotary encoders, and three push switches.

* Keyboard Maintainer: [piroridon](https://github.com/piroridon)
* Hardware Supported: *The PCBs, controllers supported*
* Hardware Availability: *Links to where you can find this hardware*

Make example for this keyboard (after setting up your build environment):

    make editor50:default

Flashing example for this keyboard:

    make editor50:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (3,3) in the matrix (stick switch push) and plug in the keyboard
* **Physical reset button**: Remove the top contoller cover. Hold the BOOT button and press the RESET button on the micro contoller board.
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
