# LRCD (Low Rez Controller DAW)
The ultimate goal of LRCD is the creation of a libretro core for music production. Yes, it's absolutely insane which is why I must do it. This is very much a wild and crazy experiment at this point but here's hoping people can eventually make songs and even albums with it! ^______^

### Design goals
* **Libretro core** - This will make coding tremendously easier on my part and also allows for [insane platform portability](https://www.libretro.com/index.php/api/).
* **Low resolution** - LRCD will run at a __fixed__ resolution of 320 x 240. This is primarily meant to save those old CRT monitors and televisions from landfills.
* **Controller input** - LRCD will be designed with a controller in mind as the only input device. Libretro's abstraction of controllers to a virtual RetroPad means you can naturally map things to whatever input device you please but the entirety of LRCD is designed assuming you will not be using a keyboard or mouse at all.
* **Digital audio workstation** _(subject to change depending on testing)_ - Most low resolution music programs are designed as trackers. LRCD is intended to be a digital audio workstation (DAW) with lots of features that DAW users are used to including audio editing. For better or worse I have used DAWs for the vast majority of the music I've made so I will be attempting to stick to this design decision as best as possible.
* **ASCII visuals** - [Code page 437 anyone?](https://en.wikipedia.org/wiki/Code_page_437) Parts of the program may not be strictly ASCII characters for sheer usability reasons (such as waveform viewing if that is a thing I end up doing) but currently I would like the program to be almost entirely ASCII characters (both code page 437 and other custom characters as need be). Maybe even slap on some shaders in your frontend of choice for that full retro vibe.


### Project status
Just got this repository together on September 14th, 2020. No code written yet but that will be changing very shortly as this is my main creative project for the foreseeable future (outside of making music with this when it's usable of course).

## License
I have not decided what license this code will be released under yet.
