**COMPLETE EMP BUILD**

  This is a low energy through hole electro magnetic pulse generator built for educational purposes.
  It uses inductive Kicback from a simple air core coil to generate broad band pulse that can glitch or reset unshielded digital circuits. Flip the top saftey , then you hold down the trigger for 2 seconds to fire max.


<img width="9923" height="7009" alt="Assembly 1 (7)" src="https://github.com/user-attachments/assets/4767b21f-ab5a-4b54-9f56-15532f4276c7" />


  ---

 ## Table of Contents

- [What is this?](#what-is-this)
- [Why I built it](#why-i-built-it)
- [How it works (in 30 secs)](#how-it-works-in-30-secs)
- [Images and diagrams](#images-and-diagrams)
- [Assembly instructions](#assembly-instructions)
  - [1. Solder the PCB](#1-solder-the-pcb)
  - [2. Wind the coil](#2-wind-the-coil)
  - [3. Prepare the enclosure](#3-prepare-the-enclosure)
  - [4. Final assembly](#4-final-assembly)
- [Safety precautions](#safety-precautions)

---

## What is this?
 A compact, battery powered device that creates a rapid magnetic field collapse,radiating an electro magnetic pulse strong enough to inter fere with nearby digital electronics.It is not a weapon.EDUCTIONAL  USE ONLY


**KEY SPECS**
|parameter|Value|
|-------|--------|
|Pulse voltage at coil|>200V|
|Effective range |20-30cm(glitch)|
|power supply|3s lipo(11.1v)|
|Max fire time|2 seconds(thermal limit) more = you have 3 seconds to get out  :)|

---

## Why I built it
I always saw lots of tutorials on youtube and always thought how cool they looked.So i thought why not build it, but most of the tutorials on youtube were either weak emps or were very vauge on how to build it.

---
## How it works (in 30 secs)
- 1. A boost converter charges a bank of capacitors to 18V
  2. A 555 timer generates a short pulse,when you press the button
  3. That pulse drives a tc4420 gate driver which turns on the mosfet
  4. Current builds up at the air core coil for like a millisecond
  5. when the mosfet turns of the magnetic field collapses
  6. This makes a voltage spike  which goes over 200v and radiates abroad band emp

---

## Images and diagrams
<img width="725" height="477" alt="image" src="https://github.com/user-attachments/assets/7a1b4cec-8334-46d7-bd85-9f664135d711" />
<img width="3508" height="2480" alt="image" src="https://github.com/user-attachments/assets/1917ba87-788c-421b-bf67-e256973f7e6e" />
<img width="806" height="586" alt="Screenshot 2026-05-26 195329" src="https://github.com/user-attachments/assets/3badfea9-b158-45d6-86af-9bccac53825d" />

---
## Assembly instructions
Get your pcb made, the gerber files are in the github.All components are marked on the pcb.
 ## 1. Solder the PCB
1. solder in order of hight, solder in resistors(r1-r7),small ceramics(c1,c5,c7)
 - then u1,u2,u3
 - then d1,l1,j1,j2,j3,j4
 - capacitors,c2,c3,c4,c6 . mind the polarity
 - q1 mossfet last
  2.clean the board with isopropyl alcohol
   
## 2. Wind the coil

- 1.Cut 40 cm of the 14awg magnet wire

  2.find a 2cm diameter cylinder(pen.pipe ect)

  3.wind 12 tight turns,make sure they touch

  4.slide it of, wrap with electrical tape

  5. leave  5cm at the end and strip the enamel and tin

  6. twist the 2 leads together

  7. measure resistance. should be 1-3 ohms . if lower add a 1 ohm resistor in series.

 ## 3. Prepare the enclosure
  
  -get the 3d printed case and line all the interior walls with copper foil other than the round emmesion  window at the front, cover the grills as well, but they are for heat dissapation.
  
  -overlap the foil and solder for continuity if needed

  
  ` solder 1 piece of wire to the foil and the other end to j4 for gnd
  
  ## 4. Final assembly
  1.mount the coil inside the case using hot glue,keep the twisted leads pointing towards the pcb area.
 <img width="1277" height="462" alt="image" src="https://github.com/user-attachments/assets/ac0dc927-f4d5-4525-b168-e40f63494eda" />

  2. place the battery in the top compartment , insert the heat set inserts , and screw the lid down, make sure the wires exit throught the bottom, slide on to the top of the case

     
  3.connect the  off board components.
 
  |Component A |Component B|
  |------------|-----------|
  |battery+|fuse|
  |fuse|master switch|
  |master switch|j2 pin 1 batt+(on pcb)|
  |battery-|j2 pin 2 batt-(on pcb)|
  |j3 pin 1 |one side of button|
  |other side of button|j3 pin2|
  |coil lead one side|j1|
  |coil lead other side|j2|
 
  
  4.place the pcb into the case , place the heat set inserts and screw the case shut.
  
----- 
## Safety precautions

. keep body and head 20-30 cm from emission window

.always discharge the coil after use, do not touch the coil while on

.do not use near pace makers , medical implants or sensitive lab equipment.

.keep a class c fire extinguisher nearby.


