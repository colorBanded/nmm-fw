# Not My Macro!
A custom macropad designed as a submission for the **2025 Summer of Code** by GitHub.
Based on the [AOI3 PCB tutorial](https://wiki.ai03.com/) with modifications for practical use.

# IMPORTANT
###### After reviewing the submission guidelines I removed a key to comply with the less than 16 inputs.

## Features
* 15 Programmable Keys
* XIAO RP2040 Microcontroller
* Highly Customizable
* Easy Dissassembly

# Cad Model:
###### For some reason Fusion 360 was bugging out while rendering the colors so enjoy the light mode experience

I engineered the top so that it slots in without any screws, making it easily detachable, I made sure that theres a tight tolerance so that it doesn't fall apart when you pick it up.
There are 15 Keys that you can customize in the firmware.

![BetterMacroKeyRender](https://github.com/user-attachments/assets/bb5b95af-da29-481a-a2dc-5593240fcb83)
Fusion 360 Renderer thingy, everything stacks (Couldn't find a proper stl for the switches and springs but those go under the top case)
![CaseView](https://github.com/user-attachments/assets/7c466d42-482d-4071-96d0-f06ad71efb84)
Default view, only two outer pieces, cool!


# PCB

I used KiCad to create the PCB assembly, used their built-in image converter to add the graphic.

![PCB DESIGN](https://github.com/user-attachments/assets/424a4fb9-f737-45d5-bc60-db2f73d22128)
![Screenshot 2025-06-28 at 12 07 04 AM](https://github.com/user-attachments/assets/bb45f7f6-9b7e-4d8a-b3e9-ed9d83466ab9)





# Firmware & Layout

I utilized the QMK firmware to handle key inputs. Use the USB C port to flash the .bin file to change layout (Better editor coming soon™)
A key changing tool like AutoHotKey is recommended, if you would like to change the keybinds yourself you can use [QMK Configurator](https://config.qmk.fm/#/atset/at16/LAYOUT_ortho_4x4)
![Screenshot 2025-06-28 at 12 07 49 AM](https://github.com/user-attachments/assets/1fb65c14-95cc-439d-9969-ce2e2befd2df)
###### This is the current key layout (DDR Reference), F13 through F24 are configured so that it doesn't interfere with any users' existing setup.


# BOM
| Item                                      | Quantity / Notes                                  |
|-------------------------------------------|----------------------------------------------------|
| Cherry MX Switches                        | 15                                                 |
| DSA Keycaps                               | 15                                                 |
| XIAO RP2040-DIP                           | 1                                                  |
| SK6812MINI LEDs                           | 2                                                  |
| Soldering Iron                            | 1                                                  |
| Case                                      | 1 (3D Printed or Laser Cut – laser cut preferred) |
| Generic Diodes (SMD D_SOD-123)            | 15                                                 |
| Assembly Time                             | Approx. 2 hours 30 minutes                         |







## Software Tools

* **PCB Design & Layout**: [KiCAD](https://www.kicad.org/)
* **3D Modeling**: [Fusion 360](https://www.autodesk.com/products/fusion-360/overview)

## References

* [AI03 Wiki](https://wiki.ai03.com/) – General information and guides on PCB design
* [Hack Club PCB Starter Guide](https://hackpad.hackclub.com/) – A beginner-friendly tutorial which this project is based on

