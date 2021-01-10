# Bakeneko 65

A simple 65% keyboard for DIYers. This project is a special homage to TGR x Singa UNIKORN 60 and OTD 356 Mini

![Bakeneko 65](https://i.imgur.com/Va1caBv.jpg?2)

## Features

- Mounting method using O-ring gasket and bottom cushion to support the PCB
- Single piece tray case
- USB-C with [Unified Daughterboard](https://github.com/ai03-2725/Unified-Daughterboard)
- QMK firmware and VIA ready
- Compatible with KBDFANS 65% plates

## Layouts

![Bakeneko 65 layouts](https://i.imgur.com/4LpvS4A.png)

## Specs

- Dimensions: 315 x 110 x 30mm
- Front height: 18.6mm
- Home row height: 31mm(with GMK keycaps and bumpons)
- Case material: Aluminum 6061-T6
- Case weight: 750g
- Case color: RAL 2002 Vermilion
- Typing angle: 6 degree
- O-ring gasket: VMQ-50(Silicone 50 duro) AS568-264 / AS568-265 for split backspace

## Mounting Style

[Bakeneko 60/65 Mounting Style - YouTube](https://youtu.be/cumnT5xGa78)

## Typing Sounds

[Bakeneko 65 Typing Sounds - YouTube](https://youtube.com/playlist?list=PLwI1Rtk5mMpzaG11CSqs7T0BvoI2UYzXa)

## Showcase

[Bakeneko 65 V2 Showcase - Imgur](https://imgur.com/a/71G36TD)

## Assets

### PCB
- [bakeneko-65/pcb](./pcb)

### Firmware
- [https://github.com/qmk/qmk_firmware/tree/master/keyboards/bakeneko65](https://github.com/qmk/qmk_firmware/tree/master/keyboards/bakeneko65)

### Case
- [bakeneko-65/case](./case)

### Plate
- [bakeneko-65/plate](./plate)

## Compatibility

### PCB

- There is no compatible PCB at the moment

### Plate

- The followings has been tested
  - [KBDFANS 65% POLYCARBONATE PLATE](https://kbdfans.com/collections/plate/products/65-polycarbonate-plate)
  - [KBDFANS 65% BRASS PLATE](https://kbdfans.com/collections/plate/products/65-brass-plate)
  - [KBDFANS 65% CNC ALUMINUM PLATE](https://kbdfans.com/collections/plate/products/65-cnc-aluminum-plate)

### Daughterboard

- Can use the one compatible with ai03's Unified Daughterboard

## Guide on how to get parts

There is only an outline here at the moment. Detailed steps will be added if needed

### PCB

- The gerber files are attached to the release page
  - These files are optimized for JLCPCB's SMT assembly service so may be required to modify when ordering from other manufacturers
  - Keep in mind that they do not solder JST connector so you must solder it yourself

### Stabilizers
- PCB Snap-in stabilizer is highly recommended
- With the screw stabilizer, the O-ring is pressed hard on the spacebar and backspace key so it has too tight feel

### Case

- I ordered a prototype from 3D Hubs
- The details of the order are as follows
  - Material: Aluminum
  - Type of Aluminum: Aluminum 6061-T6
  - Surface finish: Bead Blasted + Anodized type II (Matte)
  - Color: Specific RAL color
  - RAL code: 2002
  - Contains threads: Yes
- If you want to change the color or surface finish, you need to update notes in the technical drawing

### Plate

- Most easy way is to buy [compatible plate](#plate-1) from KBDFANS
- Or, use the dxf file for cutting service
  - I ordered a brass and aluminum plate from LaserBoost and a polycarbonate plate from BIG BLUE SAW

### Daughterboard
- Most easy way is to buy from vendors like anykeys.eu and HINEY
- Secure with four M2x4mm screws
- In my case, I ordered a Unified Daughterboard PCB from JLCPCB, purchased parts from LCSC and soldered them myself. Recommended for those who love soldering and are good at it
  - Also need to get a JST-SH 4-pin cable. I bought one from AliExpress with a 150mm length. It was a little too long, but there is no problem with using it
  - The cable should be what is called "one-to-one" or "same direction". Do not select "Reverse direction". See also [Unified Daughterboard wiki](https://github.com/ai03-2725/Unified-Daughterboard/wiki/Consumer-info) about this topic

### O-ring
- I got it from local vendor in Japan. One for about $7 ~ 8
- McMaster-Carr seems to have same spec O-ring
  - I haven't bought it and haven't tested it, but it might works
  - https://www.mcmaster.com/as568-o-rings/cross-section-shape~round/dash-number~264/hardness~durometer-50a/
  - https://www.mcmaster.com/as568-o-rings/cross-section-shape~round/dash-number~265/hardness~durometer-50a/
  
### Feet cushion
- Use Bumpons with the following spec. 3M SJ5302 will fit
  - Diameter: 7.9mm
  - Height: 2.2 mm

### Cushion to support PCB
- It's up to you to decide what to use but will share some of my experiences here
- Silicone string
  - I bought extra silicone O-rings and cut them short. Place it in the case and place the PCB on it
  - At the moment, this is my favorite way
- EVA foam
  - When I was experimenting with different materials, I just had a KBDFANS module foam, so I used it. Cut those edges to a suitable size and place in the case

## Contact

Feel free to contact me via the geekhack thread or DM if you have any questions  
https://geekhack.org/index.php?topic=107316.0

## Special thanks to

- **Elaine** for [Unikorn](https://geekhack.org/index.php?topic=98587.50). Allowed me to publish the Unikorn-inspired case as open source and encouraged me
- Of course, I also show my respect and gratitude to **yuktsi**
- **coarse** for PCB review and kind support. His great work has refined the PCB well

## Also I should mention

- **OTD** for 356 Mini. Origin of O-ring gasket mount style
- **Evy** for [Plain60 series](https://github.com/evyd13/plain60-c). I used it as a reference for my PCB design. They also answered my miscellaneous questions
- **ai03** for [MX_Alps_Hybrid](https://github.com/ai03-2725/MX_Alps_Hybrid) and [random-keyboard-parts.pretty](https://github.com/ai03-2725/random-keyboard-parts.pretty). Also got a lot of help from his discord server
- **overset** for [JP01](https://github.com/overset/JP01). The idea of publishing the case design on Onshape. After seeing their great work I switched from fusion360 to Onshape
- And many community members for giving me advice and feedback, thanks!
