TF2 RPC
---
[![pypresence](https://img.shields.io/badge/RPC-PyPresence-informational?style=for-the-badge)](https://github.com/qwertyquerty/pypresence)
[![Tailer](https://img.shields.io/badge/Log%20Reader-Tailer-informational?style=for-the-badge)](https://github.com/six8/pytailer)
[![GUI](https://img.shields.io/badge/GUI-easygui-informational?style=for-the-badge)](https://img.shields.io/badge/GUI-easygui-informational)
[![valve y](https://img.shields.io/badge/Heavy%20Update-Never-critical?style=for-the-badge)](https://www.youtube.com/watch?v=oiuyhxp4w9I)
[![steam profile](https://img.shields.io/badge/Steam%20%20Profile-EmeraldSnorlax-brightgreen?style=for-the-badge)](https://steamcommunity.com/id/EmeraldSnorlax)


![forthebadge](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)
![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)

![preview](https://i.imgur.com/rD1PXPQ.gif)


A theoretically cross-platform Discord Rich Presence Script for Team Fortress 2.

Tested on my Linux Manjaro machine, but should also work on other Linux distros, macOS and Windows.

**Windows support was done by [Kataiser](https://github.com/Kataiser), check them out!**

**JSON file made by [aUniqueUser](https://github.com/aUniqueUser/), check them out!**

Please open an issue if things go wrong.


Running from source
---
> MAKE SURE TO LAUNCH TF2 WITH THE `-condebug` LAUNCH OPTION

##### Step 1) Have Python 3 installed.
Most Linux distros have Python 3 installed by default. You may have to install it on Windows or macOS.

Download it [here](https://www.python.org/downloads/) or through your package manager.

##### Step 2) Clone this repo into a folder and install the dependencies.
Click clone. Open a Terminal / CMD / PowerShell inside the folder you cloned it into and run `pip install -r requirements.txt`.

Afterwards, all you need to do is run `python main.py` and follow the prompts.
After setting your path the first time, you will not be asked again.
Delete `tf_path.txt` to reset your path.

If it complains about not being able to find a log file, make sure you have launched TF2 with the `-condebug` launch option and double check your path.


FAQ
---

##### Is this VAC safe?

Yes. It does not mess with any of your TF2 game files and runs independent of Team Fortress 2. It simply hooks onto the `console.log` file and processes the console output, then matches it up to events.

##### It keeps saying there is no log file found!

Make sure you are launching the game with the `-condebug` launch option. Launch options can be set by right-clicking Team Fortress 2 in your Steam Library, clicking properties, and clicking Set Launch Options. This launch option tells TF2 to leave a log file, which this program can then read.

##### When is the Heavy Update coming?

[I'll let you be the judge of that.](https://www.youtube.com/watch?v=FqzpAH-WAno)

Credits
---

Log file reading uses:
https://github.com/six8/pytailer

GUI uses:
https://github.com/robertlugg/easygui

