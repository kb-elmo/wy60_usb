# WY-60 USB

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]
<a href="https://ko-fi.com/kb_elmo"><img src="https://i.imgur.com/9T0bvqO.png" alt="kofibadge" align="right"/></a>

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


#### Some pictures of the first finished PCB
[![](https://i.imgur.com/SexuyVJm.jpg)](https://i.imgur.com/SexuyVJ.jpg) [![](https://i.imgur.com/DevIs6em.jpg)](https://i.imgur.com/DevIs6e.jpg)
[![](https://i.imgur.com/V66OB8am.jpg)](https://i.imgur.com/V66OB8a.jpg) [![](https://i.imgur.com/2M1VHWPm.jpg)](https://i.imgur.com/2M1VHWP.jpg)
[![](https://i.imgur.com/meGhRlam.jpg)](https://i.imgur.com/meGhRla.jpg) [![](https://i.imgur.com/xnp9PsBm.jpg)](https://i.imgur.com/xnp9PsB.jpg)

The Case requires some modification to make the new USB port fit.  
Unfortunately the original cable cutout sits in a position where it was not possible to use it for the USB port.

---
This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
