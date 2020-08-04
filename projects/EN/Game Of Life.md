# Game-Of-Life
![](https://img.shields.io/badge/openComputers-stable-brightgreen?style=plastic)

A Lua implementation of Conway's Game of Life for OpenComputers 1.7.5. 



![Gosper Glider gun](https://github.com/VladG24YT/Game-Of-Life/blob/master/screenshots/gosper_glider_gun.png)

## Requirements
**Minimum:**<br>
![](https://github.com/Vladg24YT/Game-Of-Life/blob/master/screenshots/minimum_configuration.png)
- Screen Tier 2
- Computer Case Tier 2:
  - Graphics Card Tier 2
  - CPU Tier 1
  - 2 RAM Tier 1
  - HDD Tier 1
  - EEPROM (Lua BIOS)
- Disk Drive
  - OpenOS Floppy
  
**Recommended:**<br>
![](https://github.com/Vladg24YT/Game-Of-Life/blob/master/screenshots/recommended_configuration.png)
- Screen Tier 2
- Server Rack
- Server Tier 3:
  - Graphics Card Tier 3
  - CPU Tier 3
  - 4 RAM Tier 3.5
  - HDD Tier 3
  - EEPROM (Lua BIOS)
  - Internet Card
- Server disk drive with OpenOS Floppy

## Installation
**Online (*with internet card*):**
1. `wget https://raw.githubusercontent.com/Vladg24YT/Game-Of-Life/master/gol.lua /home/gol.lua -fq`

**Offline:**
1. Download/clone the repository (`git clone -b master --progress https://github.com/Vladg24YT/Game-Of-Life.git`)
2. Copy file `gol.lua` to `.minecraft/saves/<world-name>/opencomputers/<filesystem-uuid>/` into `/bin` or `/home` directory

## UI & How to Play
![Game UI](https://github.com/Vladg24YT/Game-of-Life/blob/master/screenshots/ui.png)<br>
**Controls:**
- **]** - proceed to next generation
- **\[** - return to previous generation
- **\\** - start self-proceeding simulation
- **/** - clear field and restart
- **\`** - exit the game
- *LMB* - invert cell's state

The game is not yet optimized, so I recommend you to change cells' states when the bottom line is green like on a screenshot above. If the bottom line is red (screenshot below), all your actions will be put into event queue, so you won't be able to immediately see which cell you're changing.<br>
![](https://github.com/Vladg24YT/Game-Of-Life/blob/master/screenshots/ui_red.png)

## Licensing

`MIT License

Copyright (c) 2020 Vladislav Gorsky

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

1. The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

2. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.`
