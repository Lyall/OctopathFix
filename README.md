# Octopath Traveler Fix
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/W7W01UAI9)</br>
[![Github All Releases](https://img.shields.io/github/downloads/Lyall/OctopathFix/total.svg)](https://github.com/Lyall/OctopathFix/releases)

This is a **work-in-progress** fix for ultrawide/narrower displays in Octopath Traveler.

## Features
- Removes pillarboxing at ultrawide or non 16:9 resolutions.
- Corrects FOV at ultrawide or non 16:9 resolutions.
- 16:9 centered HUD with fixed UI elements.
- 60 FPS cap removal.

## Installation
- Grab the latest release of OctopathFix from [here.](https://github.com/Lyall/OctopathFix/releases)
- Extract the contents of the release zip in to the game directory.<br />(e.g. "**steamapps\common\OCTOPATH TRAVELER**" for Steam).

## Configuration
- See **OctopathFix.ini** to adjust settings for the fix.

## Linux/Steam Deck
- Make sure you set the Steam launch options to `WINEDLLOVERRIDES="d3d11.dll=n,b" %command%`
<img src="https://user-images.githubusercontent.com/695941/226513105-e2aedf8f-d596-4ffb-a121-ac020d9e867f.jpg" width="646" height="113" />

## Known Issues
Please report any issues you see. (**Check the known issues list first!**)
- Screen fades and the battle wipe transitions are not spanned to fill the screen.

## Screenshots

| ![ezgif-1-3a596def59](https://user-images.githubusercontent.com/695941/227731085-44e780fb-333b-4661-8b32-88bf300696ad.gif) |
|:--:|
| Disabled pillarboxing. |

## Credits
[p1xel8ted](#) for kindly providing a copy of the game.
[Flawless Widescreen](https://www.flawlesswidescreen.org/) for the LOD fix.<br />
[Ultimate ASI Loader](https://github.com/ThirteenAG/Ultimate-ASI-Loader) for ASI loading. <br />
[inipp](https://github.com/mcmtroffaes/inipp) for ini parsing. <br />
[Loguru](https://github.com/emilk/loguru) for logging. <br />
[length-disassembler](https://github.com/Nomade040/length-disassembler) for length disassembly.
