TF2 RPC
---
[![pypresence](https://img.shields.io/badge/RPC-PyPresence-informational)](https://github.com/qwertyquerty/pypresence)
[![Tailer](https://img.shields.io/badge/Log%20Reader-Tailer-informational)](https://github.com/six8/pytailer)
[![GUI](https://img.shields.io/badge/GUI-easygui-informational)](https://img.shields.io/badge/GUI-easygui-informational)
[![valve y](https://img.shields.io/badge/Heavy%20Update-Never-critical)](https://www.youtube.com/watch?v=oiuyhxp4w9I)


![forthebadge](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)
![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)

A theoretically cross-platform Discord Rich Presence Script for Team Fortress 2


Running from source
---
> MAKE SURE TO LAUNCH TF2 WITH THE `-condebug` LAUNCH OPTION

Run `main.py` and follow the prompts.
After setting your path the first time, you will not be asked again.
Delete `tf_path.txt` to reset your path.




FAQ
---

##### Is this VAC safe?

Yes. It does not mess with any of your TF2 files and runs independent of Team Fortress 2. It simply hooks onto the `console.log` file and processes the console output, then matches it up to events.

##### It keeps saying there is no log file found!

Make sure you are launching the game with the `-condebug` launch option. Launch options can be set by right-clicking Team Fortress 2 in your Steam Library, clicking properties, and clicking Set Launch Options. This launch option tells TF2 to leave a log file, which this program can then read.




Credits
---

Log file reading is powered by:
https://github.com/six8/pytailer

GUI is done by:
https://github.com/robertlugg/easygui

