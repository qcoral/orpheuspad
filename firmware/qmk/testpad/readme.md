# orpheuspad

![orpheuspad](https://cdn.hackclub.com/019d0ee4-7ac7-7305-957e-0b8013fc038c/image.png)

a 4-key macropad with an acrylic

- Keyboard Maintainer: [alex ren](https://github.com/qcoral)
- Hardware Supported: Hackpad PCB
- Hardware Availability: Get a free kit at [hackpad.hackclub.com](https://hackpad.hackclub.com) if you're a teenager!

Make example for this keyboard (after setting up your build environment):

    make orpheuspad:default

Flashing example for this keyboard:

    make orpheuspad:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

- **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
- **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
- **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
