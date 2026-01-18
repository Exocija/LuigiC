<div align="center">
<img width="644" alt="luigi" src="https://github.com/user-attachments/assets/721c5b11-24c4-4c22-bafa-46f32610ab14" />

# LuigiC

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=6500&pause=1000&color=39FF14&background=00000000&center=true&vCenter=true&width=650&lines=I+wanna+be+a+great+plumber+like+my+brother+Mario.)](https://git.io/typing-svg)
</div>

## Overview
LuigiC is a native C AI engine for the Super Mario World C-reimplementation. It uses real-time state simulation and A* search to find the best path through a level. 

The engine runs at a stable 60 FPS, and the depth of its "thinking" scales based on how much power your hardware has.



https://github.com/user-attachments/assets/0a79bf2c-6d69-411f-a313-4cb6f14546d4

## How to Play
1. Download the latest release from the **Releases** section on the right.
2. Extract the zip file to a folder.
3. **Required:** Place your legally obtained `smw.sfc` (USA version) file into that same folder.
4. Run `smw.exe`.
5. Press **Tab** to activate the AI!

 ## Controls
 | Key | Action |
 | --- | --- |
 | **Tab** | **Toggle AI** |
 | **Q** | **Open in Map** (Custom Save/Load) |

## Compiling yourself
Due to GitHub upload limits, the full source code is available as a **zip file**
It includes Visual Studio solutions and a Makefile for MSYS2 (GCC)

## Current Limitations
- **Doors**: The AI currently can't use doors. Doors are teleports from Point A to B with no physical path between them, so the AI just sees them as "nothing".
- **Beta Phase**: This is still in Beta. Luigi might occasionally jump into a pit or do something unintended. Nobody is perfect.
- **Game Logic**: Some levels aren't 100% possible to finish yet due to bosses or complex level mechanics that don't fit into advanced pathfinding without requiring to scale the project 5x.
- **Auto-Scroll**: Auto-scroll levels are tough because the AI can't calculate a path for parts of the level that haven't loaded yet.

## Windows 11 Security Note
Windows Smart App Control (SAC) will likely block this because it’s a native C project without a paid Microsoft certificate.
- To run this, you will need to disable SAC or "Unblock" the file in Properties.
- The code does NOT contain malware. The full source code is right here for you to check.

## Legal
- **License**: MIT License.
- **Assets**: This project contains zero Nintendo assets. You must provide your own `smw.sfc` ROM to extract the game data.
- **Attribution**: This is an extension of the `snesrev/smw` project.

