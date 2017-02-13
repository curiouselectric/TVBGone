# TV-B-Gone Instructions

**By: Matthew Little**

**hello@curiouselectric.co.uk**

**Date: 13th Feb 2017**

# Overview
The TV-B-Gone switches off TVs from a distance of up to 30m. It sends out the ‘standby’ command for the top 125 European and 125 US TV specifications.
It is based upon an idea and product from Mitch Altman.
# In use 
Switch on the battery pack and point at an unwanted TV. Press the black button and the red light will flash, showing it is sending out the various TV codes. The most popular codes are sent first, but it takes over 60 seconds to run through all the codes.

# Components
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

# Tools required

# Step 1: Solder the IC socket

# Step 2: Solder the resistors

# Step 3: Solder the capacitors

# Step 4: Solder the switch

# Step 5: Solder the 16MHz resonator

# Step 6: Solder the red LED

# Step 7: Solder the transistors

# Step 8: Solder the infra-red LEDs

# Step 9: Insert programmed IC into socket. 

# Step 10: Wire up battery box

# Step 11: Attach PCB to baseplate

# Step 12: Attach battery box

# Step 13: Add 3 x AAA batteries and test!

Insert 3 AAA batteries into the battery box. Use the switch on the battery box to turn on the device. You should see the 3mm red LED flash. This means the unit is working. It will flash for around 60 seconds and then switch off. Press the black push-button switch to start the sequence again. The device sends out all the TV codes in sequence. Pressing the black button will cause it to start the sequence again.

Use a digital camera to check the IR LEDs are working. A phone camera works well for this. You should see the LEDs flashing purple, which proves the device is sending IR codes.
Note: Most popular TV codes are used first but it may take over 60 seconds to scroll through all the codes. 

# Circuit Overview

This kit is based upon a circuit originally produced by [Mitch Altman] (http://www.tvbgone.com/cfe_tvbg_main.php)

The circuit is based upon the [kit by Adafruit Industries] (http://www.ladyada.net/make/tvbgone/index.html)

Kit developed by [Matt Little at Curious Electric] (http://www.curiouselectric.co.uk)

# Circuit Schematic

# PCB overview

# Suppliers Information


