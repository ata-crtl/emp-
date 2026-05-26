**COMPLETE EMP BUILD**

  This is a low energy through hole electro magnetic pulse generator built for educational purposes.
  It uses inductive Kicback from a simple air core coil to generate broad band pulse that can glitch or reset unshielded digital circuits

![Fully assembled emp]
 <img width="841" height="572" alt="Screenshot 2026-05-26 195601" src="https://github.com/user-attachments/assets/ad124d73-5354-452f-92c6-a0361c0231ce" />


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
 A compact, battery powered device that creates a rapid magnetic field colapse,radiating an electro magnetic pulse strong enought to inter fere with nearby didgital electronics.It is not a weapon.EDUCTIONAL ONLY


**KEY SPECS**
|parameter|Value|
|-------|--------|
|Pulse voltage at coil|>200V|
|Effective range |20-30cm(glitch)|
|power supply|3s lipo(11.1v)|
|Max fire time|2 seconds(thermal limit) more = you have 3 seconds to get out  :)|

---

## Why I built it
I always saw lots of tutorials in youtube and always thought how cool they looked.So i thought why not build it, but most of the tutorials on youtube were either weak emps or were very vauge on how to build it.

---
## How it works (in 30 secs)
- 1. A boost converter charges a bank of cpacitors to 18V
  2. A 555 timer genarates a short pulse,when you press the button
  3. That pulse drives a tc4420 gate driver witch turns on the mosfet
  4. Current builds up at the air core coil for like a millisecond
  5. when the mossfet turns of the magnetic feild collapses
  6. This makes a voltage spike  witch goes over 200v and radiates abroad band emp

---

## Images and diagrams
pcb

3d model
<img width="841" height="572" alt="Screenshot 2026-05-26 195601" src="https://github.com/user-attachments/assets/6674b6d0-2263-4b90-8896-6707ec31e341" />

<img width="806" height="586" alt="Screenshot 2026-05-26 195329" src="https://github.com/user-attachments/assets/3badfea9-b158-45d6-86af-9bccac53825d" />

---
## Assembly instructions
Get your pcb made, the gerer files are in the github.All compoenets are marked on the pcb.
 ## 1. Solder the PCB
1. solder in order of hight, solder in resistors(r1-r7),small ceramics(c1,c5,c7)
 - then u1,u2,u3
 - then d1,l1,j1,j2,j3,j4
 - capacitors,c2,c3,c4,c6 . mind the polarity
 - q1 mossfet last
  2.clean the board with isopropyl alcahol
   
## 2. Wind the coil
- 1.Cut 40 cm of the 14awg magnet wire
  2.find a 2cm diamiter cylinder(pen.pipe ect)
  3.wind 12 tight turns,make sure they touch
  4.slide it of, wrrap with electrical tape
  5. leave  5cm at the end and strip the enamel and tin
  6. twist the 2 leads together
  7. meassure resistance. should be 1-3 ohms . if lower add a 1 ohm resistor in series.

 ## 3. Prepare the enclosure
  -get the 3d printed case and line all the interior walls with copper foil other than the emmsison window.
  -overlapp the foil and solder for conintuity if needed
  ` solder 1 peice of wire to the foil and the othe end to j4 for gnd
  ## 4. Final assembly
  1.mount the coil inside the case using hit glue,keep the twisted leads pointing towards the pcb area.
  2.connect the of board components.
  |compoenet A |Component B|
  |------------|-----------|
  |battery+|fuse|
  |fuse|master switch|
  |master switch|j2 pin 1 batt+(on pcb)|
  |battery-|j2 pin 2 batt-(on pcb)|
  |j3 pin 1 |one side of button|
  |other side of button|j3 pin2|
  |coil lead one side|j1|
  |coil lead other side|j2|
 
  
  3.place the pcb into the case and close.

----- 
## Safety precautions
. keep body and head 20-30 cm from emmision window
.always discharge the coil after use, do not touch the coil while on
.do not use near pace makers , medical implants or sensitive lab equipment.
.keep a class c fire estinguisher near by.
