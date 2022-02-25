# GK107_vBIOS_pkg
Kepler GK107 bios package
Overclocked to 1254.5 MHz (GPU) and 1500 MHz (MEM)

# AT FIRST
PLEASE MODIFY THIS VBIOS FOR YOUR GRAPHICS CARD!
USE THIS FILE DIRCTLY UNLESS YOUR DEVICE IS SIMILAR WITH ME!

# Quick Start
## Boost Table
| ID | Value |  Offsets  |
|----|-------|-----------|
| 00 |1254.0 | 6D97 6D98 |
| 01 | 540.0 | 6D9C 6D9D |
| 02 | 324.0 | 6DA1 6DA2 |
## Offsets Hex Data
Example: 

[A][B] [0][1] -> CD 09

"C" = [A], "D" = [B], "0" = [0], "9" = [1]

|  [A]  |  [B]  |  [0]  |  [1]  |
|-------|-------|-------|-------|
| + 8   | +0.5  | +2048 | +128  |

# Tested Device
NVIDIA GeForce GTX 650 2GB (Zotac GeForce GTX 650 2GB TSI)

# Supported Feature
- UEFI(GOP)
