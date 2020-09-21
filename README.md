# WY-60 USB

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

#### QMK compatible drop-in replacement PCB for the Wyse ASCII WY-60 keyboard
The PCB is built entirely with THT parts to keep a somewhat "vintage" look to it and it uses the fullsize 40-pin DIP package ATmega32A.
The controller is placed in the exact same location as the one on the original PCB.

<img src="https://files.elmo.space/kicad_images/wy60_usb-Front.png" alt="drawing" height="300"/>
<img src="https://files.elmo.space/kicad_images/wy60_usb-Back.png" alt="drawing" height="300"/>

### Partslist
 |Count|Part|
 |-|-|
 |1|ATmega32A 40 pin DIP (32L works too)|
 |1|40 pin DIP socket (optional but highly recommended)|
 |1|2x3 pin header 2.54mm (for ISP flashing)|
 |1|USB Mini port 5pin THT|
 |1|500 mA polyfuse|
 |2|6mm momentary push buttons|
 |1|16 MHz quarz crystal|
 |1|4.7 uF electrolytic capacitor|
 |2|100 nF ceramic disk capacitor|
 |2|22 pF ceramic disk capacitor|
 |1|10 kΩ resistor|
 |2|68 Ω resistor|
 |1|1.5 kΩ resistor|
 |2|3.6 V zener diode (DO-35 BZX55C3V6)|
 |101|universal switching diode (DO-35 1N4148)|

---
This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg