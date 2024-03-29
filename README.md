# Shifr Keyboard

Shifr (ШИФР) is a compact wireless mechanical keyboard featuring only 40 switches.

The exclusive use of through-hole components simplifies assembly and contributes to its rugged DIY aesthetic.

# Images
| Front                                      | Back                                      |
|--------------------------------------------|-------------------------------------------|
| ![front](https://raw.githubusercontent.com/CityRunner/shifr/main/img/front.png?raw=true) | ![back](https://raw.githubusercontent.com/CityRunner/shifr/main/img/back.png?raw=true) |


# Layout
Default layout is Colemak-DH with homerow mods.
![layout](https://raw.githubusercontent.com/CityRunner/shifr/main/img/layout.png?raw=true)

# Building

## Bill of materials
| Value | Designator | Footprint | Quantity |
|---|---|---|---|
| Battery | BT1 | JST_PH_S2B-PH-K_1x02_P2.00mm_Horizontal | 1 |
| Diode | D1 - D40 | Diode_DO-35 | 40 |
| Keyswitch | S1 - S40 | MX_PCB_1.00u | 40 |
| Power Switch | SW1 | SW_CuK_OS102011MA1QN1_SPDT_Angled | 1 |
| Reset Switch | SW2 | SW_TH_Tactile_Omron_B3F-10xx | 1 |
| Nice_Nano_V2 | U1 | Nice_Nano_V2 | 1 |
| Cherry MX Keycaps | - | - | 40 |
| 3.7V LiPo Battery | - | - | 1 |
| M2 Screws with Nuts | - | - | 5 |
| 3mm Spacers | - | - | 5 |

## Firmware
1. Download and unpack [misc/](https://github.com/CityRunner/shifr/tree/main/misc)firmware.zip.
2. Double-tap the Reset button on the keyboard.
3. Copy "shifr-nice_nano_v2-zmk.uf2" onto the root directory of the USB storage that appears.
4. The controller should flash the firmware and automatically restart once flashing is complete.

Source code available here: [Shifr ZMK](https://github.com/CityRunner/shifr-zmk)
