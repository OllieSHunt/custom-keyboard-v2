# Repository Layout
- `./circit_board` = KiCad design files
- `./kicad-libs` = Third party libraries that KiCad can use
- `./firmware` = QMK firmware *TODO*

# Components List
- Custom circuit board
- Raspberry Pi Pico 1 (without headers)
- SSD1306 based 128x64 OLED display (must be I2C compatible and run of 3V)
- Adafruit MiniBoost 5V @ 100mA Charge Pump - AP3602A
- 46 Gateron Low Profile Switch 2.0
- 46 Gateron compatible Low Profile Keycaps
- 46 1N4148W diodes
- 46 WS2812C-2020 LEDs
- Some stick-on silicone feet (I used 5mm tall ones)

# KiCad Libraries Used
- https://github.com/ai03-2725/MX_V2/tree/main

# KiCad Notes
Notes for my own reference:

- You can position an LED relative to the hole in the bottom of a key switch in the PCB Editor by:
  1. Right click the LED and go to "Positioning Tools" -> "Position Relative To" (or press Shift + P)
  2. Click "Select Point" then select the snap point in the center of the hole in the key switch (blue rectangle)
  3. Set the x offset to "0.7"
  3. Click "OK"
