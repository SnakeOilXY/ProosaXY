![baner logo](./doc/logo/logo.png)

<a href="https://discord.gg/WZVP2HuAag" style="height: 40px !important;"><img src="https://discordapp.com/api/guilds/851371040566673428/widget.png?style=banner2" alt="Join us on Discord" style="height: 40px !important;width: 180px !important;border-radius: 19px !important;" ></a>
<a href='https://ko-fi.com/F1F06RMBO' target='_blank'><img height='36' style='border:0px;height:40px;' src='https://cdn.ko-fi.com/cdn/kofi2.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
<a href='https://www.amazon.jp/hz/wishlist/ls/2AHXTCG01RYAZ?ref_=wl_share' target='_blank'><img height='36' style='border:0px;height:40px; !important;border-radius: 19px' src='./doc/logo/buy-me-a-spool.png' border='0' alt='Buy Me a spool at amazon Japan' /></a>


# ProosaXY
CoreXY conversion for Prusa MK3/S. This build is aiming at getting more performance out of your 6 years old machine with the lowest cost possible by re-using most the MK3/S stock parts.

## Features

- Better performance (check input-shaper graph bellow)
- Semi-enclosure by default
- ~~Dual z axis(default) or independent tripple Z axis(Optional)~~ Triple Z (independent or sync based on controller board) by default or dual Z(optional)
- Single v6 hotend(default) or mixed 2-in-1-out hotend(WIP)
- Optional AUX cooling fan
- Our industrial leading SnakeOil technology

## Status

- All the main parts design are completed. Test print result are posted in our [Discord server](https://discord.gg/WZVP2HuAag)
- ~~The first beta is planned to release at the end of May.~~ I'm a little late. Will take me a few extra weeks to work on the BOM and the CAD assembly.
- Might take a month or two for us to complete design all the optional parts. 
- For updates, please visit our [Discord server](https://discord.gg/WZVP2HuAag)

![](./doc/preview.png)

![](./doc/shaper.png)
- The input-shaper calibration is quite good for an 8mm shaft machine, in my opinion. We have a recommended acceleration of about 6000 mm/s2 (which should be used as the limit for outer perimeter acceleration), and a higher maximum acceleration/speed, depending on how fast your motor can run.
- For some extra speed boost, check my [slicer plugin](https://github.com/SnakeOilXY/klipper-dynamic-scv-slicer-post-processing) (klipper firmware only)



## Warning - read this

- This mod requires some drilling on the original frame, cutting the original motor leadscrew, and linear shafts. This drilling/cutting is easy enough to be done with a hand drill and a hacksaw **BUT THERE IS NO WAY BACK. You won't be able to convert back to the original MK3/s machine if you change your mind later.**
- Some small changes/patches might be needed after I have more test data and feedback..
- To keep the cost down and reuse old components, there are some trade-offs I made:
    - Use smooth idlers in place of toothed idlers. (I'm not a fan of this method, but we don't have much space. This kind of design seems to work fine on other machines; Prusa also uses smooth idlers on their machine too.)
    - The machine is semi-enclosed by default and will need some printed panels and a top hats to fully enclose it.
    - To match the frame height, cutting the motor leadscrew and linear shafts is required.
## BOM
[>>> Bill of materials (work in progress) <<<](./doc/BOM/readme.md)
