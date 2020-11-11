# CPE 1040 - Fall 2020

This is learning progression 004 for the Fall 2020 installment of the course CPE 1040: Introduction to Computer Engineering at MSU Denver.

<img src="images/lp004-img.jpg" width="800" />

Table of Contents
=================

* [CPE 1040 \- Fall 2020](#cpe-1040---fall-2020)
  * [Learning Progression 004: External LEDs](#learning-progression-004-external-leds)
  * [Lab kit](#lab-kit)
    * [Parts for progression](#parts-for-progression)
  * [Steps](#steps)
    * [Step 6: Electromagnetism](#step-6-electromagnetism)
      * [1\. Study](#1-study)
        * [Fundamental interaction](#fundamental-interaction)
        * [Electrostatics &amp; magenetostatics](#electrostatics--magenetostatics)
        * [Theories of electricity](#theories-of-electricity)
        * [Charge, voltage, and current](#charge-voltage-and-current)
        * [Resistance](#resistance)
        * [Ohm's law](#ohms-law)
      * [2\. Apply](#2-apply)
      * [3\. Present](#3-present)
    * [Step 7: Circuits &amp; circuit elements](#step-7-circuits--circuit-elements)
      * [1\. Study](#1-study-1)
        * [Circuits](#circuits)
        * [Short circuit](#short-circuit)
        * [Circuit elements](#circuit-elements)
        * [Kirchhoff's circuit laws](#kirchhoffs-circuit-laws)
        * [Resistors in series and in parallel](#resistors-in-series-and-in-parallel)
      * [2\. Apply](#2-apply-1)
      * [3\. Present](#3-present-1)
    * [Step 8: Multimeter](#step-8-multimeter)
      * [1\. Study](#1-study-2)
        * [Measuring voltage](#measuring-voltage)
        * [Different grounds](#different-grounds)
        * [Measuring current](#measuring-current)
        * [Measuring resistance](#measuring-resistance)
        * [Checking for continuity](#checking-for-continuity)
      * [2\. Apply](#2-apply-2)
      * [3\. Present](#3-present-2)
    * [Step 9: Basic LED circuit](#step-9-basic-led-circuit)
      * [1\. Study](#1-study-3)
      * [2\. Apply](#2-apply-3)
      * [3\. Present](#3-present-3)
    * [Step 10: micro:bit breakout board](#step-10-microbit-breakout-board)
      * [1\. Study](#1-study-4)
      * [2\. Apply](#2-apply-4)
      * [3\. Present](#3-present-4)
    * [Step 11: micro:bit GPIO pins](#step-11-microbit-gpio-pins)
      * [1\. Study](#1-study-5)
        * [micro:bit I/O](#microbit-io)
        * [Digital vs analog](#digital-vs-analog)
      * [2\. Apply](#2-apply-5)
      * [3\. Present](#3-present-5)
    * [Step 12: Screensaver extension](#step-12-screensaver-extension)
      * [1\. Study](#1-study-6)
        * [Extending a program](#extending-a-program)
        * [Defining extra rows](#defining-extra-rows)
        * [Choice of pins](#choice-of-pins)
      * [2\. Apply](#2-apply-6)
      * [3\. Present](#3-present-6)

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

##### Resistance  
- resistor
  - band theory  

##### Ohm's law

V = IR



#### 2. Apply
[[toc](#table-of-contents)]  

**TODO: Thought experiments, research, and discovery!**  

1. `[<lernact-disc>]`What if our physical world had 3 different charges instead of 2 (positive and negative)?  
2. `[<lernact-disc>]`Each fundamental interaction has a mediator particle. What is the particle for Electromagnetism?    
3. `[<lernact-disc>]`Einsein's largest contribution to science were his theories of relativity, special and general. But he did not get his Nobel Prize in Physics for either one. What did Einstein get a Nobel Prize for?    

#### 3. Present
[[toc](#table-of-contents)]  

### Step 7: Circuits & circuit elements  
[[toc](#table-of-contents)]  

#### 1. Study
[[toc](#table-of-contents)]  

##### Circuits  
- circuits  
- Kirchhoff's laws    
- parallel and in-series resistors  

##### Short circuit

##### Circuit elements  
- passive:  
  - resistor  
  - (n/a) capacitor   
  - (n/a) inductor   
- active:  
  - diode   
  - transistor  
- wires  
- voltage/current source (battery)  
- (n/a) mechanical switches  

##### Kirchhoff's circuit laws

##### Resistors in series and in parallel


#### 2. Apply
[[toc](#table-of-contents)]  

1. `[<lernact-prac>]`Take a look at the following sketch:

   <img src="images/simple-circuit.jpg" width="400" />

   It contains a simple circuit: a 3.3V voltage source (power supply) and a resistor configuration. The configuration can be a single resistor, two resistors in series or two resistors in parallel. Use Ohm's Law (V = IR) to calculate (i) the voltages across all resistors, (ii) the currents through all resistors, and (iii) the value of R, in each of the following cases:
   1. R = 330 Ohms.  
   2. R = 10 kOhms.  
   3. R = R1 + R2 = 330 Ohms + 330 Ohms.  
   4. R = R1 + R2 = 10 kOhms + 10 kOhms.  
   5. R = R1 + R2 = 330 Ohms + 10 kOhms.  
   6. R = R1 || R2 = 330 Ohms || 330 Ohms.  
   7. R = R1 || R2 = 10 kOhms || 10 kOhms.  
   8. R = R1 || R2 = 330 Ohms || 10 kOhms.  

2. `[<lernact-prac>]`  **TODO: CircuitJS**
   - [in-browser simulation](http://lushprojects.com/circuitjs/circuitjs.html) would be very nice! ([source](https://github.com/sharpie7/circuitjs1))  

   



#### 3. Present
[[toc](#table-of-contents)]  

### Step 8: Multimeter  
[[toc](#table-of-contents)]  

#### 1. Study
[[toc](#table-of-contents)]  

`[<lernact-rd>]`Our lab kit contains a sparkfun-branded `[<cept>]`[_multimeter_](https://github.com/ivogeorg/ce-learning-progression-004-06-12/blob/master/lab-kit.md#2-multimeter), a device capable of `[<cept>]`_measuring_ (meaning assigning numerical values to) electrical quantities. The [sparkfun multimeter tutorial](https://learn.sparkfun.com/tutorials/how-to-use-a-multimeter) is an excelent material that is difficult to top.  

Note that the units of measurement are from the [International System of Units](https://en.wikipedia.org/wiki/International_System_of_Units).  In particular, note the section on [prefixes](https://en.wikipedia.org/wiki/International_System_of_Units#Prefixes), which indicate the scale of the units. The multimeter has several scale settings for each measurable quantity and the choice of setting is important for the proper [care](https://github.com/ivogeorg/ce-learning-progression-004-06-12/blob/master/lab-kit.md#care-1) of the instrument.  

##### Measuring voltage  

Voltage is a measure of the difference in potential energy for the moving of electrical charge. Voltage is a `[<cept>]`_relative_ quantity, that is, we cannot the voltage of at any point in an electrical circuit without having a `[<cept>]`_reference point_. The units of measure of voltage (V) are `[<cept>]`_Volts (V)_. The reference point is usually assumed to be 0 V `[<cept>]`_ground_. Why is that? The ground of the Earth is assumed to be an infinite source or sink of electrical charge, so any point in an electrical cirtuit which is connected to the ground through a conducting wire will lose its voltage relative to it. Therefore, this is an ideal global reference point.

Voltage is measured between two points in a circuit. To measure voltage:
1. Put the multimeter (with the battery installed) dial in one of the voltage measurement positions. In this progression we will only deal with constant voltage, indicated by the symbol:  
   ```
   V ---
     ...
   ```
   The setting should be equal to or exceed the maximum value you are going to measure. For the micro:bit, which operates at 3.3V maximum voltage, the dial of our multimeter should be set to 20 V.  
2. Connect the two probes, the black one to the middle (common) port, and the red one to the port on the right. The needle-tipped probes can reach into breadboard holes.  
3. Touch the black probe to ground.  
4. Touch the red one to the point in the circuit you want to measure the voltage.  
5. Read off the value (in Volts).  

##### Different grounds

You need to make sure that you measure voltages at points in a circuit **relative to its designated ground**. Voltage values measure against the ground of a different (not directly connected) circuit are meaningless.

**Question 8.1.1:** What is the voltage you measure between the GND and 3V3 pins of the micro:bit?   
**Question 8.1.2:** What is the voltage you measure between the GND and VCC pins of the power supply?   
**Question 8.1.3:** What is the voltage you measure between the GND pin of the micro:bit and the and VCC pin of the power supply?   
**Question 8.1.4:** What is the voltage you measure between the GND pin of the power supply and the 3V3 pin of the micro:bit?   

##### Measuring current  

Current is a measure of charge traveling through a section of a circuit (be it a wire or a circuit element). Current is an `[<cept>]`_absolute_ quantity, that is, we do not need a reference point. The units of measure for current (I) are `[<cept>]`_Amperes (A)_. To measure the current flowing through a part of a circuit, we need to connect the multimeter in such a way as to have the same current flow through it as well. 

Current is measured by making the multimeter has to become "a part of" the circuit.  
1. Put the multimeter (with the battery installed) dial in one of the current measurement positions. Current settings are indicated by the symbol:  
   ```
   A ---
     ...
   ```
   The setting should be equal to or exceed the maximum value you are going to measure. For the [micro:bit](https://tech.microbit.org/hardware/1-5-revision/), the maximum current over the USB cable is 120mA and the maximum current supplied by the edge connector is 90mA.    
2. Select a point in the circuit through which the current that you want to measure flows, and break the circuit there.  
3. Connect the multimeter's probes to the two terminals of the break. The red-to-black direction should coincide with the direction of the current. (Otherwise, you will get the same value but with a negative sign in front.)  
4. Read the value (in Amperes).  

##### Measuring resistance

Resistance is the measure of opposition to the flow of electrical current through a circuit element or wire. Resistance is an absolute value. It depends only on the material and the shape of the element measured. The units of measurement are Ohms (<img src="https://render.githubusercontent.com/render/math?math=\Omega">). 

To measure resistance across a circuit element:
1. Disconnect the element and/or turn the circuit off (disconnect the power supply, battery, or other voltage or current source).  
2. Put the multimeter (with the battery installed) dial in one of the resistance measurement positions. Current settings are indicated by the symbol <img src="https://render.githubusercontent.com/render/math?math=\Omega"> (large Greek Omega). The setting should be equal to or exceed the maximum value you are going to measure. In the lab kit, we have 330<img src="https://render.githubusercontent.com/render/math?math=\Omega"> and 10<img src="https://render.githubusercontent.com/render/math?math=k\Omega"> resistors. To measure them, use the 2<img src="https://render.githubusercontent.com/render/math?math=k\Omega"> and 20<img src="https://render.githubusercontent.com/render/math?math=k\Omega"> settings, respectively.       

##### Checking for continuity  

The continuity setting is a resistance measure which emits a sound if the resistance is under a few Ohms. This means that the two points which are probed are electrically connected (as if by a wire). The symbol on the multimeter dial is:

<img src="images/multimeter-continuity-setting.jpg" width="200"/>

#### 2. Apply
[[toc](#table-of-contents)]  

**TODO: Measure everything, disconnected and connected to power supply.**

#### 3. Present
[[toc](#table-of-contents)]  

### Step 9: Basic LED circuit  
[[toc](#table-of-contents)]  

#### 1. Study
[[toc](#table-of-contents)]  

- LED current and voltage drop  

#### 2. Apply
[[toc](#table-of-contents)]  

**TODO: Measure and calculate the LED circuit. Learn the breadboard.**

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

**TODO: A selection of representative functions using R networks and LED circuits.**

#### 3. Present
[[toc](#table-of-contents)]  

### Step 12: Screensaver extension   
[[toc](#table-of-contents)]  

#### 1. Study
[[toc](#table-of-contents)]  

##### Extending a program

`[<lernact-rd>]`Extending a program is one of the most frequent tasks in software engineering. It is the complementary converse of iterative development. If you are building a large software or full-stack system, you want to implement it in steps of reasonable size, not too large and not too small. Inevitably, you will be extending an already written program.

Take a look at the following videos to see the goal for this step - extending the 5x5 LED matrix of the micro:bit to a 5x7 matrix with two external LED rows driven by micro:bit GPIO pins:
1. The [coding](https://msudenver.yuja.com/Dashboard/Permalink?authCode=1801242296&b=2060518&linkType=video) screensaver in 5x7.    
2. The [rain](https://msudenver.yuja.com/Dashboard/Permalink?authCode=710066217&b=2060531&linkType=video) screensaver in 5x7.    
3. The [frequency bars](https://msudenver.yuja.com/Dashboard/Permalink?authCode=1488262525&b=2060499&linkType=video) screensaver in 5x7.    

The first five rows are commanded with functions from the `led` namespace, while the last 2 are commanded with functions from the `pins` namespace. While analog output pins may work for the whole screensavers program, especially when we want to have different brightness (aka intensity), the coding program can use digital output pins. In this sense, the following table shows the equivalent statements:

Analog pin | Digital pin
--- | ---
`pins.analogWritePin(AnalogPin.P0, 0)` | `pins.digitalWritePin(DigitalPin.P0, 0)`
`pins.analogWritePin(AnalogPin.P0, 1023)` | `pins.digitalWritePin(DigitalPin.P0, 1)`

##### Defining extra rows

The best way to declare the extra rows is the one that will let you insert and/or modify minimal sections of the programs you are extending. Consider a 2D array, where you have two rows of 5 pins. See the following example:
```javascript
// Example 12.1.1

let led_rows : AnalogPin[] = [
    [[AnalogPin.P0], [AnalogPin.P2]],
    [[AnalogPin.P1], [AnalogPin.P8]]
]
```
Notice the following:
1. The enumerated types `AnalogPin` and `DigitalPin` are mutually exclusive. That is, you can't use the same pin as both digital and analog in the same program.  
2. You can organize the pins for the external LEDs in two different way, which equivalent except when it comes to index ordering in the 2D array selectors:
   1. By rows:
      ```javascript
      // Example 12.1.2

      let led_rows : AnalogPin[] = [
          [[AnalogPin.P0], [AnalogPin.P2], [], [], []],
          [[AnalogPin.P1], [AnalogPin.P8], [], [], []]
      ]
      ```
      in which case the selectors are ordered as `[y][x]`, and
   2. By columns:
      ```javascript
      // Example 12.1.3

      let led_cols : AnalogPin[] = [
          [[AnalogPin.P0], [AnalogPin.P1]],
          [[AnalogPin.P2], [AnalogPin.P8]],
          [[], []],
          [[], []],
          [[], []]
      ]
      ```
      in which case the selectors are ordered as `[x][y]`.

##### Choice of pins

There are a handful of factors that may affect the choice of pins for the two extra (external) LED rows:
1. We need 10 pins that are not used for anything else. This means that we are going to run them with the single-pin write and read functions of the `pins` namespace.  
2. We need the 5x5 LED matrix anaffected so that the original screensaver sub-programs display correctly. This means we cannot use the pins that are involved in running the LED matrix.  
3. We have limited breadboard real estate below the micro:bit edge connector. This means we we want to pick maximally adjacent pins to drive adjacent LEDs.  
4. The two pins used for the serial protocol I2C, namely `P19` and `P20`, would require extra `[<cept>]`_pull-down_ resistors to work, so they are not a good choice.  
5. Putting together the count of available pins, we might need to sequester one or both of the pins connected to the buttons. _Note that, if you are doing the optional challenge at the end, you will need to leave one button pin unused and make that button a mode toggle._  

#### 2. Apply
[[toc](#table-of-contents)]  

1. `[<lernact-prac>]`Build the two external rows of LEDs and program a row to continuously move up and down the 7 vertical positions (5 from the micro:bit LED matrix and 2 on external LEDs driven by micro:bit pins).  
2. `[<lernact-prac>]`Extend the code-writing program to work with the 7 rows of LEDs.  
3. `[<lernact-prac>]`Extend the rain screensaver to work with the 7 rows of LEDs.  
4. `[<lernact-prac>]`Extend the frequency bar screensaver to work with the 7 rows of LEDs.  
5. `[<lernact-prac>]`**[Optional challenge, max 10 extra step points]** Extend the whole screesavers application to work with the 5x7 format and tag it `v2.0`.  

#### 3. Present
[[toc](#table-of-contents)]

In the [programs](programs) directory:
1. Add your program from 12.2.1 with filename `microbit-program-12-2-1.js`.  
2. Add your program from 12.2.2 with filename `microbit-program-12-2-2.js`.  
3. Add your program from 12.2.3 with filename `microbit-program-12-2-3.js`.  
4. Add your program from 12.2.4 with filename `microbit-program-12-2-4.js`.  
5. Add your program from 12.2.5 with filename `microbit-program-12-2-5.js`.  

In the [Lab Notebook](README.md):

1. Link to the program from 12.2.1.  
2. Link to the program from 12.2.2.  
3. Link to the program from 12.2.3.  
4. Link to the program from 12.2.4.  
5. Link to the program from 12.2.5.  
6. Link to the tag for program from 12.2.5.  
