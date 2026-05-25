**COMPLETE EMP BUILD**

  This is a low energy through hole electro magnetic pulse generator built for educational purposes.
  It uses inductive Kicback from a simple air core coil to generate broad band pulse that can glitch or reset unshielded digital circuits

![Fully assembled emp]
 phots go here . 

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
- [Wiring diagram](#wiring-diagram)
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

wring diagram 
