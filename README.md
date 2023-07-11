![baner logo](./doc/logo/logo.png)

<a href="https://discord.gg/WZVP2HuAag" style="height: 40px !important;"><img src="https://discordapp.com/api/guilds/851371040566673428/widget.png?style=banner2" alt="Join us on Discord" style="height: 40px !important;width: 180px !important;border-radius: 19px !important;" ></a>
<a href='https://ko-fi.com/F1F06RMBO' target='_blank'><img height='36' style='border:0px;height:40px;' src='https://cdn.ko-fi.com/cdn/kofi2.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
<a href='https://www.amazon.jp/hz/wishlist/ls/2AHXTCG01RYAZ?ref_=wl_share' target='_blank'><img height='36' style='border:0px;height:40px; !important;border-radius: 19px' src='./doc/logo/buy-me-a-spool.png' border='0' alt='Buy Me a spool at amazon Japan' /></a>


# ProosaXY
CoreXY conversion for Prusa MK3/S. This build is aiming at getting more performance out of your 6 years old machine with the lowest cost possible by re-using most the MK3/S stock parts.

## 1. Features

- Better performance (check input-shaper graph bellow)
- Semi-enclosure by default. Panels mount and top hat parts will be added later.
- ~~Dual z axis(default) or independent tripple Z axis(Optional)~~ Triple Z (independent or sync based on controller board) by default or dual Z(optional)
- Single v6 hotend(default) or mixed 2-in-1-out hotend(WIP)
- Optional AUX cooling fan
- Our industrial leading SnakeOil technology

## 2. Status

- All the main parts design are completed. Test print result are posted in our [Discord server](https://discord.gg/WZVP2HuAag)
- All part STLs are exported. 
- Full BOM added 2023/07/11
- I'm working on a simple build log/manual. 
- For updates, please visit our [Discord server](https://discord.gg/WZVP2HuAag)



![](./doc/img/shaper.png)
- The input-shaper calibration is quite good for an 8mm shaft machine, in my opinion. We have a recommended acceleration of about 6000 mm/s2 (which should be used as the limit for outer perimeter acceleration), and a higher maximum acceleration/speed, depending on how fast your motor can run.
- For some extra speed boost, check my [slicer plugin](https://github.com/SnakeOilXY/klipper-dynamic-scv-slicer-post-processing) (klipper firmware only)

## 3. Warning - read this

- This mod requires some drilling on the original frame, cutting the original motor leadscrew, and linear shafts. This drilling/cutting is easy enough to be done with a hand drill and a hacksaw **BUT THERE IS NO WAY BACK. You won't be able to convert back to the original MK3/s machine if you change your mind later.**
- Some small changes/patches might be needed after I have more test data and feedback..
- To keep the cost down and reuse old components, there are some trade-offs I made:
    - The machine is semi-enclosed by default and will need some printed panels and a top hats to fully enclose it.
    - To match the frame height, cutting the motor leadscrew and linear shafts is required.
## BOM

[>>> Bill of materials <<<](./doc/BOM/readme.md)

## 4. Test run videos and images

### 4.1 Prusa Mk4 12mins bonker benchy 


<table>
    <thead>
        <tr>
            <th></th>
            <th align="center">Mk4 bonker benchy</th>
            <th align="center">Real-world print</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Video</td>
            <td align="center"><a href="https://youtu.be/1M5wx4Q0jNs" rel="nofollow">
            <img src="https://img.youtube.com/vi/1M5wx4Q0jNs/0.jpg" alt="bonker benchy test print"/></a></td>
            <td align="center"><a href="https://youtu.be/Dink3JQ" rel="nofollow">
            <img src="https://img.youtube.com/vi/Dink3JQ-bNY/0.jpg" alt="normal test print"/></a></td>
        </tr>
        <tr>
            <td>Description</td>
            <td>I use the setting Prusa used on their mk4 12 mins benchy with accel pump up a little.</br>
            <a href="https://github.com/SnakeOilXY/ProosaXY/tree/master/doc/img/bonker-benchy">Print result (images)</a></br>
            <img src="https://github.com/SnakeOilXY/ProosaXY/blob/master/doc/img/setting_benchy.png?raw=true"></td>
            <td><img src="https://github.com/SnakeOilXY/ProosaXY/blob/master/doc/img/setting_standard.png?raw=true"></td>
        </tr>
    </tbody>
</table>

### 4.2 Images
![](./doc/img/preview-01.jpg)
![](./doc/img/preview-02.jpg)
![](./doc/img/preview-03.jpg)
![](./doc/img/preview-04.jpg)
![](./doc/img/preview-05.jpg)
![](./doc/img/preview-06.jpg)
![](./doc/img/preview-07.jpg)

## 5. Copyright Notice

This printer design use the following parts from other opensource project:
- Fan duct from [EVA 2.3](https://github.com/EVA-3D/eva-main)
- Filament sensor from [Bear Extruder And X Axis (BearExxa)](https://github.com/gregsaun/bear_extruder_and_x_axis)
- Sherpa mini extruder from [Annex Engineering](https://github.com/Annex-Engineering/Sherpa_Mini-Extruder)
- Original hardware from [Prusa MK3](https://github.com/prusa3d/Original-Prusa-i3)

### License

- [Sherpa mini extruder](https://github.com/Annex-Engineering/Sherpa_Mini-Extruder) is an original work of [Annex Engineering](https://github.com/Annex-Engineering), modified parts using their source code/design files are re-released under [ANNEX Engineering License](https://github.com/Annex-Engineering/ANNEX-Engineering-License-Agreement/blob/main/LICENSE.md).
- [EVA2](https://github.com/EVA-3D/eva-main) is an original work of [EVA-3D](https://github.com/EVA-3D), modified parts using their source code/design files are re-released under [GNU General Public License v3.0](https://github.com/EVA-3D/eva-main/blob/main/LICENSE)
- [Bear Extruder And X Axis (BearExxa)](https://github.com/gregsaun/bear_extruder_and_x_axis) is an original work of [Grégoire Saunier](https://github.com/gregsaun), modified parts using their source code/design files are re-released under [GNU General Public License v3.0](https://github.com/gregsaun/bear_extruder_and_x_axis/blob/master/LICENSE)
- [Prusa MK3](https://github.com/prusa3d/Original-Prusa-i3) is an original work of [Prusa3D](https://github.com/prusa3d), modified parts using their source code/design files are re-released under [GNU General Public License v2.0](https://github.com/prusa3d/Original-Prusa-i3/blob/MK3S/LICENSE)
- This printer design(ProosaXY), it's document and software are released under [GNU General Public License v3.0](https://github.com/SnakeOilXY/ProosaXY/blob/master/LICENSE)
