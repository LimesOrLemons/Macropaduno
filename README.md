# Macropaduno

An ESP32-S3 handheld controller with a custom PCB and 3D-printed enclosure for numerous programmable functions.

## Overview

Welcome to **Macropaduno**, a custom-designed handheld controller powered by an ESP32-S3. This is the second iteration of the design, significantly expanded to pack maximum functionality into a compact layout for advanced programming and testing.

<img width="540" height="473" alt="image" src="https://github.com/user-attachments/assets/46d9c421-b917-4ace-8474-79143efa8b20" />

## Features & Hardware Specs

* **Microcontroller:** ESP32-S3
* **Connectivity:** Bluetooth & Wi-Fi
* **Power Management:** Integrated battery management, internal power system, and a voltage booster (3.3V to 5V)
* **Audio:** Onboard speaker driven by an audio amplifier
* **Visuals:** OLED screen, camera module (OV2640), and addressable RGB LED
* **Input Controls:**
* 9x Mechanical key switches
* 2x Pressable joysticks
* 1x Pressable rotary encoder switch


* **Expansion:** Dedicated servo/header port for external peripherals and motors

## Project Journey & Lessons Learned

This design represents about a month of intensive work on the digital and schematic design side. Moving from a much smaller initial prototype, this version integrates all peripheral components onto a single custom PCB paired with a 3D-printed enclosure.

While the form factor turned out a bit bulkier than originally planned, it serves as an exceptional foundation for future iterations. Key engineering takeaways from this project include:

* Introduction to KiCad schematic and PCB layout & practices
* C++ firmware development for the ESP32-S3 and electronic components
* Planning for acoustic chambers, battery integration, and mechanical clearance in 3D CAD (modeled in Onshape, with future plans to explore SolidWorks for professional CAD workflows).
* Identifying areas for future optimization, such as transitioning to 4-layer boards and component stacking for tighter spatial efficiency.

<img width="1914" height="630" alt="image" src="https://github.com/user-attachments/assets/d316855e-669c-47ca-9fdd-cc07aa70f807" />

## Version 1 Prototype
Here is what the v1 version of the macropad looked like:

<img width="985" height="769" alt="image" src="https://github.com/user-attachments/assets/c295aa06-f533-4bc0-9724-3527e8b2c9aa" />

## Version 2 Prototype
Here is what the v2 version of the macropad looked like:

<img width="700" height="514" alt="image" src="https://github.com/user-attachments/assets/61c17ec5-3e17-4e7a-b6d9-7158cd16a89c" />


## Acknowledgements & Credits

Special thanks to the open-source community and creators who shared CAD models and reference files used during the design process:

* [603040 600mAh LiPo Battery Cell on GrabCAD](https://grabcad.com/library/603040-600mah-lipo-battery-cell-1)
* [Cherry MX Switches on GrabCAD](https://grabcad.com/library/cherry-mx-switches-mx-1)
* [OV2640 Camera Model on GrabCAD](https://grabcad.com/library/ov2640-for-esp32-cam-1)
* [JST PH 2.0mm Connector Pack on GrabCAD](https://grabcad.com/library/jst-ph-2-0mm-connector-pack-through-hole-smt-ds1066-1)
* [Rotary Encoder on GrabCAD](https://grabcad.com/library/rotary-encoder-17)
* [0.91" OLED 128x32 Display on GrabCAD](https://grabcad.com/library/oled-0-91-128x32-1)
* [CherryMX GitHub Library by hineybush](https://github.com/hineybush/CherryMX/tree/master)
