# ProosaXY MINI considerations

This is a small documentation page to guide you about some concerns.

## 1. Slicer settings

This is the setings I'm using actually.

* 0.2mm layer height
* Wall count: 5
* Top/bottom layer: 5
* Infill: 30%, with any gyroid variant

## 2. Filament

It depends on what you're looking for, PETG can withstand if you are not pushing the limits and you are only printing PLA, but honestly I recommended to print all parts with high temperature resistant filament.

If you want to reuse the stock motor steppers (that it's not recommended) you need at least ABS+GF or PC+ABS for motor mounts, stock steppers can do 10-15K accels with 200-250mm/s with 0.6-0.65amps but running very hot. (+80ºC)

Check the shrinkage of the filament !

## 3. Parts required

The ProosaXY MINI uses a mix of standard ProosaXY parts and specific MINI parts.


| Group   | From     | Part                       | Quanty | Notes                                                                 |
| :-------- | ---------- | ---------------------------- | -------- | ----------------------------------------------------------------------- |
| XY Axis | ProosaXY | motor-support-body-left    | 1      |                                                                       |
| XY Axis | ProosaXY | motor-suport-body-right    | 1      |                                                                       |
| XY Axis | ProosaXY | motor-support-slider-left  | 1      |                                                                       |
| XY Axis | ProosaXY | motor-support-slider-right | 1      |                                                                       |
| XY Axis | ProosaXY | left-motor-mount-base      | 1      | This part will be hot                                                 |
| XY Axis | ProosaXY | left-motor-mount-cap       | 1      |                                                                       |
| XY Axis | ProosaXY | left-motor-mount-spacer    | 1      | This part will be hot                                                 |
| XY Axis | ProosaXY | right-motor-mount-base     | 1      | This part will be hot                                                 |
| XY Axis | ProosaXY | right-motor-mount-cap      | 1      |                                                                       |
| XY Axis | ProosaXY | right-motor-mount-spacer   | 1      | This part will be hot                                                 |
| XY Axis | ProosaXY | motor-shaft-spacer         | 1      |                                                                       |
| XY Axis | MINI     | y-carrier-cap              | 2      |                                                                       |
| XY Axis | MINI     | y-carrier-LM10**L**UU      | 2      | Take care, LM10LUU for long bearing.                                  |
| XY Axis | MINI     | y-rod-cap                  | 4      |                                                                       |
| XY Axis | ProosaXY | long-spacer                | 2      |                                                                       |
| XY Axis | ProosaXY | short-spacer               | 8      |                                                                       |
| XY Axis | MINI     | rod-mount                  | 4      |                                                                       |
| Z Axis  | ProosaXY | z-rod-bottom-mount-right   | 2      |                                                                       |
| Z Axis  | ProosaXY | z-rod-top-mount-right      | 2      |                                                                       |
| Z Axis  | ProosaXY | z-rod-bottom-mount-left    | 2      |                                                                       |
| Z Axis  | ProosaXY | z-rod-top-mount-left       | 2      |                                                                       |
| Z Axis  | MINI     | bed-cable-cover-top        | 1      |                                                                       |
| Z Axis  | MINI     | bed-cable-cover-bottom     | 1      |                                                                       |
| Z Axis  | MINI     | extrusion-end-logo         | 1      | MMU version available                                                 |
| Z Axis  | ProosaXY | Z-motor-mounter            | 2      |                                                                       |
| Z Axis  | ProosaXY | bed-LM8UU-mounter          | 4      |                                                                       |
| Z Axis  | ProosaXY | pom-nut-mounter            | 2      |                                                                       |
| Z axis  | MINI     | prusa-mini-bed-helper      | 1      | You can fit without.... but I do not recommend. This part will be hot |
| Panels  | MINI     | back-panel-bottom-left     | 1      |                                                                       |
| Panels  | MINI     | back-panel-bottom-right    | 1      |                                                                       |
| Panels  | MINI     | back-panel-top-left        | 1      |                                                                       |
| Panels  | MINI     | back-panel-top-right       | 1      |                                                                       |
| Panels  | MINI     | back-panel-connector       | 1      | MMU version available                                                 |
| Panels  | MINI     | bottom-pnnel-back-left     | 1      |                                                                       |
| Panels  | MINI     | bottom-panel-back-right    | 1      |                                                                       |
| Panels  | MINI     | bottom-panel-front-left    | 1      |                                                                       |
| Panels  | MINI     | bottom-panel-front-right   | 1      |                                                                       |
| Panels  | ProosaXY | bottom-panel-connector     | 1      |                                                                       |
| Panels  | ProosaXY | bottom-panel-clip          | 6      |                                                                       |
| Panels  | ProosaXY | y-cover-cap-mirror         | 2      | Optional, but 100% recommended                                        |
| Panels  | ProosaXY | y-cover-cap                | 2      | Optional, but 100% recommended                                        |
| Panels  | MINI     | y-cover-body               | 4      | Optional, but 100% recommended                                        |
| Panels  | ProosaXY | panel-clip-housing         | 12     | Only if you will put side panels                                      |
| Panels  | ProosaXY | panel-clip-inner           | 12     | Only if you will put side panelsOptiona                               |
| Panels  | ProosaXY | proosaxy-mini-big-logo     | 1      | MMU version available                                                 |
| Others  | ProosaXY | foot-mounter-mX            | 4      | Pick your version                                                     |

Toolhead section it depends of what do you want to fit, the following parts are intended to be paired with TZ-V6 2.0 hotend with V6 style nozzle. (V6 nozzle are 2mm taller of TZ nozzles) and magneto filament cutter from VzBot. We will not support the Prusa Mini hotend due their poor performance and tied to heatcreep due the ausence of real heatbreak.

The toolhead it's the same of the ProosaXY, if you don't want TZ-V6 select wathever you want :)

If you don't want the filament cutter, just drill the PTFE hole with 4mm bit and fit longer PTFE tube.


| Group    | From                                                                                                                                                                                | Part                      | Quanty | Notes                                                                                       |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------- | -------- | --------------------------------------------------------------------------------------------- |
| Toolhead | ProosaXY                                                                                                                                                                            | cable-end-mounter         | 1      |                                                                                             |
| Toolhead | ProosaXY                                                                                                                                                                            | strain-relief-end-mounter | 1      |                                                                                             |
| Toolhead | ProosaXY                                                                                                                                                                            | Duct v2.1 straight low    | 1      | This part will be very hot                                                                  |
| Toolhead | ProosaXY/MMU                                                                                                                                                                        | Extruder mount - Sherpa   | 1      | Stronger version that standard, This part will be very hot                                  |
| Toolhead | ProosaXY/MMU                                                                                                                                                                        | Hotend mount - TZ-V6      | 1      | This part will be very hot, drill with 4mm bit if you don't want to use the filament cutter |
| Toolhead | <a href="https://github.com/Annex-Engineering/Annex-Engineering_User_Mods/tree/main/Extruders/Sherpa_Mini/Extruder_Mods/Gryp2-Housing_Core_with_filament_sensor">Annex user mod</a> | sherpa-core-with-d2f      | 1      | Sherpa mini core with D2F sensor, This part will be very hot                                |
| Toolhead | ProosaXY/MMU                                                                                                                                                                        | sherpa-idler-arm-strong   | 1      | Stronger idler arm for fine sensor activation, This part will be very hot                   |
| Toolhead | ProosaXY                                                                                                                                                                            | c_front_body              | 1      | This part will be very hot                                                                  |
| Toolhead | ProosaXY                                                                                                                                                                            | c_back_body               | 1      | This part will be very hot                                                                  |
| Toolhead | ProosaXY                                                                                                                                                                            | back-fan-mounter          | 1      | This part will be very hot                                                                  |
| Toolhead | ProosaXY                                                                                                                                                                            | bottom-bearing-cap        | 1      | critical part, This part will be very hot                                                   |
| Toolhead | ProosaXY                                                                                                                                                                            | carrier-body              | 1      | critical part, This part will be very hot                                                   |
| Toolhead | ProosaXY                                                                                                                                                                            | duct-spacer               | 1      | This part will be very hot                                                                  |
| Toolhead | ProosaXY                                                                                                                                                                            | hotend-bottom-mount       | 1      | This part will be very hot                                                                  |
| Toolhead | ProosaXY                                                                                                                                                                            | probe-mounter             | 1      | This part will be very hot                                                                  |
| Toolhead | ProosaXY                                                                                                                                                                            | top-bearing-cap           | 1      | critical part, This part will be very hot                                                   |
| Toolhead | ProosaXY                                                                                                                                                                            | belt-holder               | 2      | Critical part, This part will be very hot                                                   |
| Toolhead | ProosaXY                                                                                                                                                                            | belt-tensioner-cap        | 2      | This part will be very hot                                                                  |
| Toolhead | ProosaXY                                                                                                                                                                            | back-fan-spacer           | 3      | This part will be very hot                                                                  |

Electronics,  you will need to complete your print list depending the components you will fit.


| Group       | From     | Part                          | Quanty | Notes                                             |
| ------------- | ---------- | ------------------------------- | -------- | --------------------------------------------------- |
| Electronics | MINI     | Proosa-mini-lcd-holder        | 1      | MMU version available                             |
| Electronics | MINI     | proosa-mini-xxxmmm-PSU-holder | 1      | Pick your version, measure your PSU               |
| Electronics | MINI     | ebb42-din-mount               | 1      | Only of you are using this MCU, uses 50mm spacing |
| Electronics | MINI     | buddy-mcu-din-mount           | 1      | Uses 50mm spacing                                 |
| Electronics | MINI     | buddy-mcu-fan-mount           | 1      |                                                   |
| Electronics | MINI     | buddy-mcu-clip                | 1      |                                                   |
| Electronics | MINI     | low-profile-din-clip          | 6      | 50mm spacing                                      |
| Electronics | ProosaXY | Raspberry pi mounts           | 1      |                                                   |
| Electronics | ProosaXY | LRS-25-5 PSU mounts           | 1      |                                                   |
| Electronics | ProosaXY | bottom-din-holder             | 2      |                                                   |
| Electronics | ProosaXY | back-din-holder               | 4      |                                                   |
| Electronics | ProosaXY | optional_din-ziptie           | n      |                                                   |

Tools and jigs


| Group | From     | Part                      | Quanty | Notes                                                              |
| :------ | ---------- | --------------------------- | -------- | -------------------------------------------------------------------- |
| Tools | ProosaXY | 2020 drill jig            | 1      | Only if you need drill the extrusions                              |
| Tools | ProosaXY | 2020 holder               | 1      | Only if you need drill the extrusions                              |
| Tools | ProosaXY | 45mm mark jig             | 1      | Only if you need drill the extrusions                              |
| Tools | ProosaXY | mr115 holder drill guide  | 1      | Only if you need drill the extrusions                              |
| Tools | ProosaXY | bearing-stack-holder-tool | 1      | Needed to fit the F623 bearin stacks                               |
| Tools | ProosaXY | belt-position-jig         | 1      | Helper to situate the same distance on each side to tune the belts |
| Tools | MINI     | z-rod-mount-aligner       | 1      | You can use instead a caliper and measure 48mm from the extrusion. |
| Tools | MINI     | silicon-mod-jig           | 1      |                                                                    |
