# Lab kit

A take-home lab kit for CPE 1040, LP004-005.

## 1. Breadboard

A breadboard is a plate with through-holes and electrical connections for use with hands-on circuit building and prototyping. This is the white plastic block shown on the picture below. There are also a [power supply](https://www.sparkfun.com/products/13032) (with a [wall adapter](https://www.sparkfun.com/products/15314) and a [microbit connector](https://www.sparkfun.com/products/13989).

<img src="images/01-breadboard.jpg" width="600" />  

The power supply is connected to one end of the breadboard along the short side. The microbit connector is connected to the middle of the long side of the breadboard, along the A column (when looking at the side opposite to the one where the power supply is installed). Take a look at the next pictures:

<img src="images/02-breadboard-assembled.jpg" width="400" />  | <img src="images/15-power-supply-rails.jpg" width="400" /> | <img src="images/14-mb-breakout-col-a.jpg" width="400" />
--- | --- | ---


### Guide

SparkFun, who assembled the lab kit for us, has very thorough guides:
1. For [using a breadboard](https://learn.sparkfun.com/tutorials/how-to-use-a-breadboard/all), including the power supply. Pay special attention to how the breadboard rows and columns are connected. This is something you have to get used to.    
2. For [hooking up the micro:bit to the breadboard](https://learn.sparkfun.com/tutorials/microbit-breakout-board-hookup-guide).  

### Care

Pay attention to these care directions:
1. Take a look at this [image from the SparkFun guide](https://cdn.sparkfun.com/r/600-600/assets/2/f/9/d/a/513a1dfbce395fe524000001.JPG) for the correct connection of the power supply. The [header pins](https://www.mouser.com/images/samtec/images/samtec_mtms_SPL.jpg), of which it has 2 groups of 4 on both sides, have to be inserted into the rails of the breadboard, in the first two rows on one end, with the VCC label on the side of the red rail line and the GND on the side of the blue rail line.  
2. To make the power supply more stable, you can use a piece of hard putty underneath it.  

   <img src="images/12-uhu-tac.jpg" width="200"/> | <img src="images/16-power-supply-pad.jpg" width="200"/> 
   --- | ---

3. The power supply has two tiny switches, one for ON-OFF and one for 3.3V-5V. _Handle the switches very gently._ When the power supply is on, a red LED is lit up. It is brighter for 5V than for 3.3V. We will use 3.3V for our projects.  
4. The micro:bit works at 3.3V, but we won't be powering it from the power supply, but through the USB cable or battery. _Do not plug the micro:bit connector into one of the rails!_  
5. Pushing in the micro:bit connector takes quite a bit of force. _Use a hard flat surface (e.g. scissors) to push straight down, to avoid mangling the header pins._  

<img src="images/13-mb-breakout-scissors.jpg" width="200"/>  

## 2. Multimeter

The [multimeter](https://www.sparkfun.com/products/12966) is a device that can measure electrical quantities, namely voltage (in Volts), current (in Amperes), resistance (in Ohms), as well as continuity of a circuit.  
| | |
|---|---|
| <img src="images/03-multimeter-backside.jpg" width="300"/> | You need to open the flap on the back to connect the 9V PP3 battery |
| <img src="images/04-multimeter-battery-in.jpg" width="300"/> | There is only one way you can connect the battery leads to the wire connector |
| <img src="images/05-multimeter-front-probes.jpg" width="300"/> | Multimeter needs probes to measure the right circuit quantity |
| <img src="images/06-multimeter-front-needle-probes.jpg" width="300"/> | Needle tipped probles can reach inside a breadboard hole |

### Guide

The sparkfun [multimeter tutorial](https://learn.sparkfun.com/tutorials/how-to-use-a-multimeter) is comprehensive and covers a lot of topics. _Consider this required reading._  

### Care

Follow these directions for safety and tool care:
1. Always connect the black probe to the middle hole, named COM, which stands for common.  
2. For this course, connect the red probe to the right-hand hole. You will not need to use the left-hand hole, as we are not going to generate such a large current (10 Amperes).  
3. The dial on the face of the multimeter chooses the function. Mind the following two points:
   1. Never select a current measument function (A) to measure voltage. Never select a voltage measurement function (V) to measure current.  
   2. Always select a function with a rating larger than you expect your quantity to be. For example, to measure voltages around 3.3V, set the dial to 20V:
   
      |   |   |
      |---|---|
      <img src="images/18-measuring-3v3.jpg" width="200"/>  | <img src="images/17-multimeter-closeup.jpg" width="200"/>  

4. The needle-tipped probes are extremely sharp. _Always replace the caps when you are leaving them unattended and/or not using them._  

## 3. Wires

## 4. Resistors

## 5. Semiconductors

### Guide

#### Diodes

#### Transistors

### Care

## 6. Light-emitting diodes

### Guide

### Care




