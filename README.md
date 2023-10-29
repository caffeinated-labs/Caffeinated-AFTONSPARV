# Caffeinated AFTONSPARV

This small PCB replaces the original board inside your [AFTONSPARV Planet lamp](https://www.ikea.com/us/en/p/aftonsparv-led-decorative-light-planet-shape-multicolor-20559209/).
You can connect it to your smart home using the ESP32 with common firmware.

## BOM
| Reference         | Value                  | Qty | LCSC                |
| ----------------- | ---------------------- | --- | ------------------- |
|C1, C4, C7, C11    | 100nF                  | 4   | C14663              |
|C2                 | 100µF 35V              | 1   | C2831717            |
|C3, C6, C9, C10    | 4.7uF                  | 4   | C560882             |
|C5                 | 22pF                   | 1   | C105620             |
|L1                 | 10uH                   | 1   | C38117              |
|Q1-Q3              | AO3400A                | 3   | C347475             |
|R1-R3, R7-R10, R14 | 10kΩ                   | 8   | C98220              |
|R4-R6              | 20Ω                    | 3   | C22950              |
|R11                | 1Ω                     | 1   | C22936              |
|R12                | 100kΩ                  | 1   | C25803              |
|R13                | 22.1kΩ                 | 1   | C25961              |
|SW1                | SW_Push                | 1   | C2910751            |
|U1                 | ESP32-C3-MINI-1-[H/N]4 | 1   | C2934569 / C2838502 |
|U2                 | SY8201ABC              | 1   | C108052             |

[BOM Tool](bom/ibom.html)
