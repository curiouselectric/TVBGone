<p align="center">
<img  src="https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/CuriousElectricCompany_Logo_Web_Header.png?raw=true" width="200" >
</p>


# TV-B-Gone Instructions

**By: Matthew Little,      Date: 13th Feb 2017**

**hello@curiouselectric.co.uk**

# Overview
The TV-B-Gone switches off TVs from a distance of up to 30m. It sends out the ‘standby’ command for the top 125 European and 125 US TV specifications.
It is based upon an idea and product from [Mitch Altman](http://www.tvbgone.com/).

<div class="testImage">

![Image of TV-B-Gone](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_Final.png?raw=true "Built TV-B-Gone PCB")

</div>

# In use
Switch on the battery pack and point at an unwanted TV. Press the black button and the red light will flash, showing it is sending out the various TV codes. The most popular codes are sent first, but it takes over 60 seconds to run through all the codes.

# Components

## PCB and components

![Image of components](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/ComponentsRef.jpg?raw=true "Kit Components")

| Component Name      | Value     | Quantity  | Reference   |
|-----------------    |-------    |-----------|-----------  |
| Capacitor           | 100uf     | 1         | C1          |
| Capacitor           | 0.1uf     | 1         | C2          |
| LED IR 950nm        |           | 4         | D1,D2,D3,D4 |
| LED Red 5mm         |           | 1         | D5          |
| MicroController     | ATTiny85  | 1         | IC1         |
| IC 8pin Socket      |           | 1         |             |
| Battery Holder      |           | 1         | P1          |
| Resistor            | 1k        | 2         | R1,R4       |
| Resistor            | 10k       | 2         | R2,R3       |
| Transistor  PNP     | BC640     | 1         | Q1          |
| Transistor  NPN     | BC548     | 4         | Q2,Q3,Q4,Q5 |
| Switch              |           | 1         | SW1         |
| Resonator           | 8MHz      | 1         | Y1          |

## Baseplate parts

![Image of base plate parts](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_122831_sm.jpg?raw=true "Base plate parts")

| Component Name      | Info                      | Quantity  |
|-----------------    |-------                    |-----------|
| Base Plate          | 3mm Laser-cut plastic     | 1         |
| M3 Nuts             | BZP metal                 | 8         |
| M3 12mm Screws      | BZP metal                 | 4         |
| Sticky Pad          |                           | 1         |

# Tools required

![Image of tools](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/Tools.JPG?raw=true "Tools required")

The main tools required are: Soldering Iron, solder and side cutters. A screw driver and small set of pliers is also useful.

[Here is a good getting started guide to soldering](https://mightyohm.com/files/soldercomic/FullSolderComic_EN.pdf)

# Step 1: Solder the IC socket
![Solder IC Socket](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_1.png?raw=true "Solder the IC Socket")

Ensure the IC (integrated circuit) socket is soldered with the notch on the holder aligned with the notch shown on the silkscreen of the PCB.

# Step 2: Solder the resistors
![Solder Resistors](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_2.png?raw=true "Solder the resistors x 4")

These resistors are:

| Value               | Colours                    | Reference |
|-----------------    |-------                     |-----------|
| 1k ohm              | Brown, Black, Red, Gold    | R1        |
| 10k ohm             | Brown, Black, Orange, Gold | R2        |
| 10k ohm             | Brown, Black, Orange, Gold | R3        |
| 1k ohm              | Brown, Black, Red, Gold    | R4        |

The resistors do not have a polarity and can be soldered either way around.

# Step 3: Solder the capacitors
![Solder Capacitors](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_3.png?raw=true "Solder the capacitors x 2")

The capacitors are:

| Value              | Identification                                       | Reference |
|-----------------   |-------                                               |-----------|
| 100uF              | Black cylinder with white stripe. "100uF" Marked     | C1        |
| 0.1uF              | Cream box with ".1J63" Markings                      | C2        |


C1 does not have a polarity and can be soldered either way around.

C2 **is** polarised. The long lead is positive (+ve). There is a white stripe down the negative side. Ensure the positive and negative leads align correctly. The positive lead needs to fit in the hole with the "+" symbol near it.

# Step 4: Solder the switch
![Solder Switch](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_4.png?raw=true "Solder the switch")

The switch fits in to the four holes marked "SW1" and "START".

# Step 5: Solder the 8MHz resonator
![Solder Resonator](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_5.png?raw=true "Solder the resonator")

The resonator is the three-pin device and is soldered into the three holes near Y1. It does not matter which way round the device is soldered in.

# Step 6: Solder the red LED
![Solder red LED](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_6.png?raw=true "Solder the 3mm red LED")

The red LED is soldered into the holes marked "D5". The LED has a polarity with the long lead being positive (+ve) and the shorter lead is negative. Also the negative side has a flat side on the plastic LED enclosure. Ensure the flat side aligns with the flat side of the LED. The flat side is the -ve. The rounded side is the +ve.

# Step 7: Solder the transistors
![Solder Transistors](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_7.png?raw=true "Solder the 5 x Transistors")

There are 5 transistors to solder in (4 of BC548 and 1 of BC640):

| Value             | Marking  | Reference |
|-----------------  |-------   |---------  |
| BC640             | BC640    | Q1        |
| BC548             | BC548    | Q2        |
| BC548             | BC548    | Q3        |
| BC548             | BC548    | Q4        |
| BC548             | BC548    | Q5        |

The transistors have a polarity and the flat side of the transistor should align with the longer flat side of the silk screen. Please check the photo for more detail.

# Step 8: Solder the infra-red LEDs
![Solder IR LEDs](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_8.png?raw=true "Solder the 4 x IR LEDs")

The IR LEDs are transparent plastic and, to the human eye, they cannot be seen flashing. They emit light outside of human eye spectrum.

The IR LEDs are soldered into the holes marked "D1-D4". The LED has a polarity with the long lead being positive (+ve) and the shorter lead is negative. Also the negative side has a flat side on the plastic LED enclosure. Ensure the flat side aligns with the flat side of the LED. The flat side is the -ve. The rounded side is the +ve.

![Solder IR LEDs](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_8_b.png?raw=true "Solder the 4 x IR LEDs")

Bend the leads of the LED at 90 degrees so that they shine away from the PCB, as shown. If the circuit board is to be mounted onto the plastic base, then wait until the board is screwed down before doing this step.

# Step 9: Insert programmed IC into socket.
![Insert IC](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_9.png?raw=true "Insert the ATTiny85 IC")

The programmed IC (an ATTint85 microcontroller) must be inserted the correct way. There is a small dot on the IC which indicates pin 1. This dot should be aligned with the notch shown on the PCB silkscreen and on the IC socket.

![Insert IC](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/ATtiny85-500x500.jpg?raw=true "Insert the ATTiny85 IC")

# Step 10: Wire up battery box
![Solder Battery Box](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_Final.png?raw=true "Solder on the battery box")

Push the wires from the battery box through the larger holes next to the word "Battery". These can then be knotted to provide strain relief.

The red wire is the battery positive (+ve) and is soldered to the hole in P1 with the **square** pad, next to the **"+"** symbol. The black wire is soldered into the other pad.

# Step 11: Attach PCB to baseplate

Use the 4 machine screws and the 8 nuts to hold the PCB to the baseplate as shown here:

![PCB baseplate](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_122853_sm.jpg?raw=true "Screws through baseplate")
![PCB baseplate](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_122948_sm.jpg?raw=true "Nuts onto screws")
![PCB baseplate](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_123023_sm.jpg?raw=true "PCB onto Screws")
![PCB baseplate](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_123059_sm.jpg?raw=true "PCB onto Screws")

# Step 12: Attach battery box

Use the double-sided sticky pad to affix the battery box to the baseplate. Some of the battery holders do **NOT** have an on/off switch (it is not needed as the unit powers down into an ultra-low power state until the "START" button is pressed). You may need to cut the sticky pad into two pieces.

![Stick down battery box](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_123221_sm.jpg?raw=true "Stick down battery box")
![Stick down battery box](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_123233_sm.jpg?raw=true "Stick down battery box")
![Stick down battery box](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_123313_sm.jpg?raw=true "Stick down battery box")
![Stick down battery box](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_123318_sm.jpg?raw=true "Stick down battery box")

# Step 13: Add 3 x AAA batteries and test!

![Insert batteries](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_123338_sm.jpg?raw=true "Insert 3 x AAA batteries")
![Ready to go](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_123415_sm.jpg?raw=true "Ready to go!")

This device takes 3 x AAA batteries. Slide off the top cover of the battery holder and insert them as shown in the battery holder.
The unit should spring into action with the red LED flashing. Each time the red LED flashes then a different TV 'OFF' code is sent. This means the unit is working.

If no sign of red LED flashing then please double check your soldering, the orientation and placement of all components and the IC orientation.

It will flash for around 60 seconds and then switch off. Press the black push-button switch to start the sequence again. The device sends out all the TV codes in sequence. Pressing the black button will cause it to start the sequence again.

Use a digital camera to check the IR LEDs are working. A phone camera works well for this. You should see the LEDs flashing purple, which proves the device is sending IR codes. Here is a photo of the IR flashes taken on a phone camera:

![Test](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_LED_Test.png?raw=true "Test the unit")

**_Note:_ Most popular TV codes are used first but it may take over 60 seconds to scroll through all the codes.**


# Circuit Overview

This kit is based upon a circuit originally produced by [Mitch Altman](http://www.tvbgone.com/cfe_tvbg_main.php)

The circuit is based upon the [kit by Adafruit Industries](http://www.ladyada.net/make/tvbgone/index.html)

Kit developed by [Matt Little at Curious Electric](http://www.curiouselectric.co.uk)

# Circuit Schematic

![Circuit Schematic](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/Schematic_TVBGone.png?raw=true "The Circuit Schematic")

[And here as a .pdf](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/TVBGoneSchematic.pdf)

# PCB overview

![PCB](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_overview.jpg?raw=true "The PCB overview")

[And here as a .pdf](https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/TVBGone_PCB.pdf)

# Suppliers Information

We would like you to be happy with this kit. If you are not happy for any reason then please contact us and we will help to sort it out.

Please email **hello@curiouselectric.co.uk** with any questions or comments.

Please tweet us at **@curiouselectric**

If any parts are missing from your kit then please email **hello@curiouselectric.co.uk** with details and, if possible, where the kit was purchased.

More technical information can be found via **www.curiouselectric.co.uk**

The GITHUB repository for all the files is: **https://github.com/curiouselectric/TVBGone**

This kit has been designed and produced by:

<p align="center">
<b>The Curious Electric Company</b><br>
hello@curiouselectric.co.uk<br>
www.curiouselectric.co.uk<br>
Hopkinson,<br>
21 Station Street,<br>
Nottingham,<br>
NG2 3AJ, UK<br>
<br>
<img src="https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/CuriousElectricCompany_Logo_Round_Logo.png?raw=true" width="150" align="middle">
</p>
