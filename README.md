
# Crazy_Leds

## Overview

Crazy_Leds is the powerful 6W RGB individually addresible led lighting designed for 7 inch quadcopters. 
If you fell that regular LED strip brings not enough light and power — this is very good choise for you. 
Crazy_leds is very useful in many applications: night time flying, maintaing the orientaintion of the craft, separating you from the competition. 
And it just looks amazing! 

![3d view](https://github.com/Kiriil-Shark05/Crazy_Leds/blob/main/3D/png/main_PCB_3D_preview.png "3d view")



## Hardware

The project includes two types of PCBs: the main PCB and PDBs. 
Let's look at each type in detail:



### Main PCB
The main PCB is the lighting board itself. It based on **3W RGB LEDs**. 
Here is some specifications of them:

![leds_specifications](https://github.com/Kiriil-Shark05/Crazy_Leds/blob/main/PCB/leds_specifications/leds_specifications.png "leds_specifications")

Another important component is **WS2811 LED driver**. It drives the LEDs 
and makes the lighting individually addressable. Thanks to the LED driver, 
we can change the color and brightness of every particular LED by a single data line. 
There is also a possibility to drive multiple lighting boards by connecting the data output 
of one into the data input of another.

WS2811 can't drive high power LEDs by itself because it has low output current. 
So, the signal from the LED driver boosts by MOSFETs.

Some resistors and capacitors perfom auxiliary function in the circuit. The board also has a two-position switch to power off the lighting.

The board also has a two-position switch, so you can always physically power off the lighing.

The full list of the components and the schematic you can find in the project repository.

| PCB Layout        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| ![leds_specifications](https://github.com/Kiriil-Shark05/Crazy_Leds/blob/main/PCB/layouts/main_PCB_layout.png "leds_specifications")      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |


























(Из чего ёще состоит плата)

(размеры, layouts, может 3d view)

(характериситки платы)
### PDBs