# Repository Layout
- `./circit_board` = KiCad design files
- `./kicad-libs` = Third party libraries that KiCad can use
- `./firmware` = QMK firmware *TODO*

# Components List
- Custom circuit board
- Raspberry Pi Pico (without headers, and I use the original Pi Pico, not the v2)
- Gateron Low Profile Switch 2.0, brown (can be swapped for any other colour, you need 46 of these)
- WOMIER Low Profile Keycaps (can be swapped for any other compatible keycaps, you need 46 of these)
- 1N4148W diodes (you need 46 of these)
- WS2812C-2020 LEDs (*TODO: how many do I need?*)

# KiCad Libraries Used
- https://github.com/ai03-2725/MX_V2/tree/main

# KiCad Notes
Notes for my own reference:

- You can position an LED relative to the hole in the bottom of a key switch in the PCB Editor by:
  1. Right click the LED and go to "Positioning Tools" -> "Position Relative To" (or press Shift + P)
  2. Click "Select Point" then select the snap point in the center of the hole in the key switch (blue rectangle)
  3. Click "OK"
