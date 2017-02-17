<p align="center">
<img  src="https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/CuriousElectricCompany_Logo_Web_Header.png" width="200" >
</p>

# TV-B-Gone Instructions

**By: Matthew Little,      Date: 13th Feb 2017**

**hello@curiouselectric.co.uk**

# Overview
The TV-B-Gone switches off TVs from a distance of up to 30m. It sends out the ‘standby’ command for the top 125 European and 125 US TV specifications.
It is based upon an idea and product from Mitch Altman.

![Image of TV-B-Gone] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_Final.png "Built TV-B-Gone PCB")




# In use 
Switch on the battery pack and point at an unwanted TV. Press the black button and the red light will flash, showing it is sending out the various TV codes. The most popular codes are sent first, but it takes over 60 seconds to run through all the codes.

# Components

![Image of components] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/Components.png "Kit Components")

| Component Name      | Value     | Quantity  | Reference   |
|-----------------    |-------    |-----------|-----------  |
| Capacitor           | 22uf      | 1         | C1          |
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

![Image of base plate parts] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_122831_sm.jpg "Base plate parts")

| Component Name      | Info                      | Quantity  | 
|-----------------    |-------                    |-----------|
| Base Plate          | 3mm Laser-cut plastic     | 1         |
| M3 Nuts             | BZP metal                 | 8         |
| M3 12mm Screws      | BZP metal                 | 4        |
| Sticky Pad          |                           | 1         |

# Tools required
![Image of tools] 

# Step 1: Solder the IC socket
![Solder IC Socket] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_1.png "Solder the IC Socket")

# Step 2: Solder the resistors
![Solder Resistors] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_2.png "Solder the resistors x 4")

# Step 3: Solder the capacitors
![Solder Capacitors] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_3.png "Solder the capacitors x 2")

# Step 4: Solder the switch
![Solder Switch] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_4.png "Solder the switch")

# Step 5: Solder the 16MHz resonator
![Solder Resonator] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_5.png "Solder the resonator")

# Step 6: Solder the red LED
![Solder red LED] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_6.png "Solder the 3mm red LED")

# Step 7: Solder the transistors
![Solder Transistors] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_7.png "Solder the 5 x Transistors")

# Step 8: Solder the infra-red LEDs
![Solder IR LEDs] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_8.png "Solder the 4 x IR LEDs")

# Step 9: Insert programmed IC into socket. 
![Insert IC] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_9.png "Insert the ATTiny85 IC")

# Step 10: Wire up battery box
![Solder Battery Box] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_Final.png "Solder on the battery box")

# Step 11: Attach PCB to baseplate
![PCB baseplate] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_122853_sm.jpg "Screws through baseplate")
![PCB baseplate] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_122948_sm.jpg "Nuts onto screws")
![PCB baseplate] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_123023_sm.jpg "PCB onto Screws")
![PCB baseplate] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_123059_sm.jpg "PCB onto Screws")

# Step 12: Attach battery box
![Stick down battery box] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_123221_sm.jpg "Stick down battery box")
![Stick down battery box] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_123233_sm.jpg "Stick down battery box")
![Stick down battery box] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_123313_sm.jpg "Stick down battery box")
![Stick down battery box] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_123318_sm.jpg "Stick down battery box")


# Step 13: Add 3 x AAA batteries and test!

![Insert batteries] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_123338_sm.jpg "Insert 3 x AAA batteries")
![Ready to go] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/IMG_20160113_123415_sm.jpg "Ready to go!")

Insert 3 AAA batteries into the battery box. Use the switch on the battery box to turn on the device. You should see the 3mm red LED flash. This means the unit is working. It will flash for around 60 seconds and then switch off. Press the black push-button switch to start the sequence again. The device sends out all the TV codes in sequence. Pressing the black button will cause it to start the sequence again.

Use a digital camera to check the IR LEDs are working. A phone camera works well for this. You should see the LEDs flashing purple, which proves the device is sending IR codes. Here is a photo of the IR flashes taken on a phone camera:
 
![Test] (https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/PCB_LED_Test.png "Test the unit")

**_Note:_ Most popular TV codes are used first but it may take over 60 seconds to scroll through all the codes.**



# Circuit Overview

This kit is based upon a circuit originally produced by [Mitch Altman] (http://www.tvbgone.com/cfe_tvbg_main.php)

The circuit is based upon the [kit by Adafruit Industries] (http://www.ladyada.net/make/tvbgone/index.html)

Kit developed by [Matt Little at Curious Electric] (http://www.curiouselectric.co.uk)

# Circuit Schematic

# PCB overview

# Suppliers Information

We would like you to be happy with this kit. If you are not happy for any reason then please contact us and we will help to sort it out. 

Please email **hello@curiouselectric.co.uk** with any questions or comments.

Please tweet us at **@curiouselectric**

If any parts are missing from your kit then please email **hello@curiouselectric.co.uk** with details and, if possible, where the kit was purchased.

More technical information can be found via **www.curiouselectric.co.uk**

The GITHUB repository for all the files is: **https://github.com/curiouselectric/TVBGone**

This kit has been designed and produced by:

__The Curious Electric Company__

**hello@curiouselectric.co.uk**

**www.curiouselectric.co.uk**

Hopkinson, 

21 Station Street, 

Nottingham, 

NG2 3AJ, UK

<p align="center">

<img src="https://github.com/curiouselectric/TVBGone/blob/master/TVBGone_Instructions/Photos/CuriousElectricCompany_Logo_Round_Logo.png" width="300" align="middle">
</p>

