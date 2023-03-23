# R4ver's Quest ASL Thumb Parameters (VRC/CVR)

After a long time I'm finally releasing my take on an animation controller for ASL use, utilizing thumb parameters!

This animation controller is aimed towards Quest users (sorry Index people <3) and gives you the entire ASL alphabet on
one hand with a couple easy combo gestures for extra sign usage (More on that below).

The animation controller is ambidextrous, meaning you'll be able to do everything on both left and right hand.
the couple combos that are in the controller are also ambidextrous.

NOTE: I still have some small issues to iron out for the CVR release, which is why it's not currently in the repo.

## How to install
Grab the latest release from the release page, unpack the .zip file somewhere easily accesible, go into the folder and open unity package in your unity project, navigate to the
recently added folder named `R4vers Thumbparams Quest` and  simply drag the animation controller
into your gesture layer on your `VRC Avatar Descriptor`.

## How to use
In the unpacked release folder you'll find a folder named `rosc_thumbparams_standalone`. This is a standalone version of my thumb parameter module (OSC) which interacts with OpenVR to read your thumb position on 
your Quest controller as well as Index controllers and assign a number to a given thumb position.

1. Start SteamVR / Game.
2. Navigate to the `rosc_thumbparams_standalone` folder.
3. Find the .exe file named `thumbparameters` and launch it.
6. Open up the game if you haven't already and try any of the combos in the list below.

## Gesture layout
I've tried my best to make the overall flow of things feel natural to what you are doing in real life,
with some exceptions. 

I will be refering to inputs in the following way:

Top = `Y / B` | Bottom = `X / A` | Both = `B + A / Y + X` | Stick = `Thumb stick` | Grip = `Grip` | Trigger = `Index Finger Trigger Press` | Rest = `Resting Finger on Trigger` | OP = `opposite`

| Letter / Gesture |                       Controller Input                       |
|:----------------:|:------------------------------------------------------------:|
|         A        |                          Top + Rest                          |
|         B        |                         Top + Trigger                        |
|         E        |                         Bottom + Rest                        |
|         F        |                        Both + Trigger                        |
|         G        |                          Top + Grip                          |
|         I        |                          Both + Grip                         |
|         J        |                         I + Draw a J                         |
|         K        |                             Both                             |
|         M        |                          Both + Rest                         |
|         N        |                      Both + Rest + Grip                      |
|         P        |                K, but look up how to hold hand               |
|         Q        |                G, but look up how to hold hand               |
|         R        |                              Top                             |
|         S        | Bottom + Rest + Grip (I still recommend drawing the S Shape) |
|         T        |                       Top + Rest + Grip                      |
|         U        |                             Stick                            |
|         V        |                            Bottom                            |
|         W        |                       Bottom + Trigger                       |
|         X        |                         Bottom + Grip                        |
| 25 / Middle down |                   Stick + OP Bottom + Grip                   |
|      Flat B      |                   Stick + OP Both + Rest                     |
|      Flat O      |                 Stick + OP Both + Rest + Grip                |
|      Bend V      |                        Stick + OP Both                       |
|       IRLY       |                  Stick + OP Bottom + Trigger                 |
|        ILY       |              Stick + OP Bottom + Trigger + Grip              |

*(Please let me know if I messed up in the list. Either open an issue here on github or mention it for me in VRC or CVR should you encounter me)*

NOTE: I've excluded general letters that are not directly using the parameters, such as `C`, `D`, `H`, `L`, `O`, `Y` and `Z`.

# Issues
If you encounter any issues, feel free to open an issue here on github as I won't help on eg. Discord to keep things organized and easier to track.

Do feel free to ask me questions in VRC or CVR should you see me and I'm not currently occupied with something else. 

# Changelog
1.1.0
- Added `Flat B` + changed how you active `Falt B` and `Flat O` (see above)
- Fixed minor issues.

1.0.0
- Initial release

# License
The MIT License (MIT)

Copyright (c) 2021 Timeless

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.