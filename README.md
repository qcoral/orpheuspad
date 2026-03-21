# Orpheuspad!

![picture of orpheuspad](https://cdn.hackclub.com/019d0ee4-7ac7-7305-957e-0b8013fc038c/image.png)

Orpheuspad is a 4 key macropad with a rotary encoder, an OLED Display. It also has 2 WS2812B Leds, and uses QMK firmware

I designed this as a reference/example macropad for [hackpad](https://hackclub.hackpad.com), an program where you can learn how to design your own macropad and get it for free. It contains an implementation of every common part!

## Features:

- Staggered acrylic display!
- 128x32 OLED Display for animations!
- An EC11 Rotary encoder for whatever you want
- 2 WS2812B RGB LEDs. One for underglow, and one that diffuses throughout the case.
- 4 Cherry MX-style keys!
- [VIA](https://www.caniusevia.com/) support!

## CAD Model:

Everything fits together using 5 M3 Bolts and heatset inserts. 4 for the case, one for the PCB. Also, it has a 5 degree tilt

It has 3 separate printed pieces. The angle, the base where the PCB sits, and the top cover. it also has 2 acrylic plates. One to cover the electronics, the other to hold the switches

<img src=assets/cad.png alt="Schematic" width="500"/>

Made in Fusion360. Nifty

## PCB

Here's my PCB! It was made in KiCad. The silkscreen was imported from a Figma image.

<img src=assets/schematic.png alt="Schematic" width="300"/>

<img src=assets/pcb.png alt="Schematic" width="300"/>

I used MX_V2 for the keyswitch footprints. I think in retrospect, I should've added a ground plane

## Firmware Overview

This hackpad uses [QMK](https://qmk.fm/) firmware for everything.

- the rotary encoder changes volume. press to mute
- The 4 keys currently act as macros I dynamically change in VIA.
- The OLED is a cat!! Bongocat!! :3

<img src=assets/bongocat.png alt="Bongo Cat" width="300"/>

I might add more in the future! That's it for now

## BOM:

Here should be everything you need to make this hackpad

- 4x Cherry MX Switches
- 4x DSA Keycaps
- 5x M3x5x4 Heatset inserts
- 3x M3x16mm SHCS Bolts
- 2x M3x12mm SHCS Bolts
- 5x 1N4148 DO-35 Diodes.
- 2x WS2812B LEDs
- 1x 0.91" 128x32 OLED Display
- 1x EC11 Rotary Encoder
- 1x XIAO RP2040
- 1x Case (3 printed parts, 2 laser cut parts)
