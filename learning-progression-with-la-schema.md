# CPE 1040 - Fall 2020

This is learning progression 004 for the Fall 2020 installment of the course CPE 1040: Introduction to Computer Engineering at MSU Denver.

<img src="images/lp004-img.jpg" width="800" />




## Learning Progression 004: External LEDs
[[toc](#table-of-contents)]  

This progression introduces fundamentals of computing, including the binary system of data representation as well as the basics of memory and processing. We introduce assembly language in the context of a minimal instruction set processor. This is where the lowest layer of the software stack and the highest layer of the hardware stack coexist, and where user programs are translated into machine code and executed by the processor one instruction at a time. This is also the level of computing which directly correpsonds to the simplest theoretical models of a computer. We also introduce the input-output capabilities of the micro:bit and build an external circuit to serve as an extension to the built-in 5x5 LED matrix to run our Screensavers program on.

## Lab kit
[[toc](#table-of-contents)]  

The lab kit is described in detail in a [separate page](lab-kit.md). Please, make sure you read the care and safety instructions embedded for most of the kit components.    

### Parts for progression  
[[toc](#table-of-contents)]  

1. Breadboard.  
2. Breadboard power supply with wall plug.  
3. micro:bit breakout board (connector).  
4. 330 Ohm resistor (10 count).  
5. LEDs (10 count).  
6. Wires.  

## Steps

### Step 6: Electromagnetism
[[toc](#table-of-contents)]  

#### 1. Study
[[toc](#table-of-contents)]  

##### Fundamental interaction

##### Electrostatics & magenetostatics

- electrostatics (rubbing amber, etc.)  

##### Theories of electricity
- theories of electricity  
  - current as motion of charge  
  - Maxwell's equations  
  - quantum electrodynamics  

##### Charge, voltage, and current
- charge, voltage, current  


#### 2. Apply
[[toc](#table-of-contents)]  

1. `[<lernact-disc>]`What if our physical world had 3 different charges instead of 2 (positive and negative)?  
2. `[<lernact-disc>]`Each fundamental interaction has a mediator particle. What is the particle for Electromagnetism?    
3. `[<lernact-disc>]`Einsein's largest contribution to science were his theories of relativity, special and general. But he did not get his Nobel Prize in Physics for either one. What did Einstein get a Nobel Prize for?    

#### 3. Present
[[toc](#table-of-contents)]  

### Step 7: Circuits & circuit elements  
[[toc](#table-of-contents)]  

#### 1. Study
[[toc](#table-of-contents)]  

##### Resistance  
- resistor
  - band theory  
- Ohm's law

##### Circuits  
- circuits  
- Kirchhoff's laws    
- parallel and in-series resistors  

##### Circuit elements  
- (n/a) capacitor   
- (n/a) inductor   
- diode  
- wires  
- voltage/current source (battery)  
- (n/a) mechanical switches  
- [in-browser simulation](http://lushprojects.com/circuitjs/circuitjs.html) would be very nice! ([source](https://github.com/sharpie7/circuitjs1))  


#### 2. Apply
[[toc](#table-of-contents)]  

#### 3. Present
[[toc](#table-of-contents)]  

### Step 8: Multimeter  
[[toc](#table-of-contents)]  

#### 1. Study
[[toc](#table-of-contents)]  

##### Measuring voltage  
- voltage  

##### Measuring current  
- current  

##### Measuring resistance
- resistance  

##### Checking for continuity  
- diode/continuity  

#### 2. Apply
[[toc](#table-of-contents)]  

#### 3. Present
[[toc](#table-of-contents)]  

### Step 9: Basic LED circuit  
[[toc](#table-of-contents)]  

#### 1. Study
[[toc](#table-of-contents)]  

- LED current and voltage drop  

#### 2. Apply
[[toc](#table-of-contents)]  

#### 3. Present
[[toc](#table-of-contents)]  

### Step 10: micro:bit breakout board
[[toc](#table-of-contents)]  

#### 1. Study
[[toc](#table-of-contents)]  

[Hookup guide](https://learn.sparkfun.com/tutorials/microbit-breakout-board-hookup-guide)  

#### 2. Apply
[[toc](#table-of-contents)]  

1. `[<lernact-prac>]`Run the program from the guide, using any 3 LEDs of different color.  
2. `[<lernact-prac>]`Run with 5 LED circuits.    
3. `[<lernact-prac>]`5 LED circuits driven by 5 evenly offset sinusoids to produce a ripple effect.    


#### 3. Present
[[toc](#table-of-contents)]  

### Step 11: micro:bit GPIO pins
[[toc](#table-of-contents)]  

#### 1. Study
[[toc](#table-of-contents)]  

##### micro:bit I/O
- digital/analog functions  
- write out to drive external LED circuit  
- read in (simple resistor and LED circuits)  

##### Digital vs analog  
- digital vs analog (binary vs continuous-level signal)  
- calibration of analog in  
- write out and read in together to close the external-circuit loop  
- resources:
  - [edge connector](https://tech.microbit.org/hardware/edgeconnector/#pins-and-signals)  
  - [pin:out](https://microbit.pinout.xyz/)  

#### 2. Apply
[[toc](#table-of-contents)]  

#### 3. Present
[[toc](#table-of-contents)]  

### Step 12: Screensaver extension   
[[toc](#table-of-contents)]  

#### 1. Study
[[toc](#table-of-contents)]  

- two extra rows for a 5x7 matrix   
- extension of code and rain, separately  
- remove one button and convert the other to a mode toggle  
- parametrize `screensavers.js` as follows:  
  - 5x5 to 5x7  
  - internal LEDs with `led` commands, external LEDs with `pin` commands  

#### 2. Apply
[[toc](#table-of-contents)]  

#### 3. Present
[[toc](#table-of-contents)]  



